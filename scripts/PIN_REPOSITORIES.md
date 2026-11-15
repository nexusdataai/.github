# Pin repositories on the org profile (one-time UI step)

GitHub does **not** expose a public API for organization pinned repositories. After repos are public and the profile README is merged, an **org owner** completes this in the browser (about 30 seconds).

## Repositories to pin (public view)

1. [nexus-docs](https://github.com/nexusdataai/nexus-docs)
2. [nexus-ontology](https://github.com/nexusdataai/nexus-ontology)
3. [nexus-ai-engine](https://github.com/nexusdataai/nexus-ai-engine)
4. [nexus-simulator](https://github.com/nexusdataai/nexus-simulator)
5. [nexus-deployer](https://github.com/nexusdataai/nexus-deployer)
6. [nexus-cli](https://github.com/nexusdataai/nexus-cli)

## Steps

1. Open [https://github.com/nexusdataai](https://github.com/nexusdataai) while signed in as an **org owner**.
2. In the right sidebar, set **View as** → **Public** (optional, to match what visitors see).
3. Click **Pin repositories** or **Customize pins**.
4. Select the six repositories listed above (do **not** pin `.github` unless you want it in the grid).
5. Click **Save pins**.

Verify with:

```bash
gh api graphql -f query='{ organization(login: "nexusdataai") { pinnedItems(first: 10, types: REPOSITORY) { nodes { ... on Repository { name } } } } }'
```