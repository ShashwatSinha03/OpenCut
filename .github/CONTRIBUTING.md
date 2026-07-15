# Contributing to OpenCut

Thanks for your interest in OpenCut! Right now the project is being rewritten from the ground up — the architecture is still being designed.

## Current Status

OpenCut is **not yet accepting external pull requests** while the new architecture stabilizes. What's coming:

- An Editor API
- First-class third party plugins
- Desktop, mobile, and browser from one codebase (Rust core)
- MCP server (for AI agents)
- Headless mode (automation, batch rendering)

You can find the previous stable version at [opencut-app/opencut-classic](https://github.com/opencut-app/opencut-classic).

## How to Get Involved

- **Follow along**: Star the repo and watch for releases.
- **Ask questions**: Join our [Discord](https://discord.gg/zmR9N35cjK) or open a [GitHub Discussion](https://github.com/OpenCut-app/OpenCut/discussions).
- **Report bugs**: Open a [bug report](https://github.com/OpenCut-app/OpenCut/issues/new?template=bug_report.yml).
- **Suggest features**: Open a [feature request](https://github.com/OpenCut-app/OpenCut/issues/new?template=feature_request.yml).

## Development Setup

If you want to explore the code or build locally:

1. Install [proto](https://moonrepo.dev/proto):
   ```sh
   bash <(curl -fsSL https://moonrepo.dev/install/proto.sh)
   ```
2. From the repo root:
   ```sh
   proto use
   moon run web:dev       # localhost:5173
   moon run api:dev       # localhost:8787
   moon run desktop:dev   # see apps/desktop/README.md
   ```

## Code of Conduct

Please note that this project follows a [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful and inclusive.
