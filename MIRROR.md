# Where this code lives

This repository is the standalone home of the `canli-markets-mcp` package, published so the server can be installed, scanned
and reviewed on its own. It is imported from the `mcp-markets/` directory of
[arhancanli/canlicapital](https://github.com/arhancanli/canlicapital/tree/main/mcp-markets), which is where changes are
made and tested; this repository is updated from it at each release.

Imported from canlicapital commit `583e8ddce24da5cdb1355e90cc41f28056fb88aa` (tag `markets-mcp-v0.17.0`).

- npm: https://www.npmjs.com/package/canli-markets-mcp
- MCP Registry: `io.github.arhancanli/canli-markets-mcp`
- All Canli servers in one, five tools in context: `npx -y canli-mcp` (https://www.npmjs.com/package/canli-mcp)
- Hosted (no install), inside canli-mcp: https://canlicapital.com/mcp/canli
- About it: https://canlicapital.com/mcp-servers/markets

Files owned by this repository and kept across syncs: `.github/` (CI, CodeQL, OpenSSF Scorecard and Dependabot),
`.gitignore`, `MIRROR.md`, `glama.json`, and the digest-pinned base image in `Dockerfile`.

`test/default-risk.test.mjs` reads files from the parent monorepository, so it runs in canlicapital CI against these exact
source bytes and is left out of this repository's CI.
