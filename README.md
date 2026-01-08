# Asuré Open Solutions

Collection of open-source apps and experiments under the Asuré umbrella.

This repo uses Git submodules to keep individual apps in their own repos while still providing a single hub to clone.

## Included apps
- `apps/asure-flow` - AsuréFlow (real-time transcription + AI notes)

## Getting started
Clone with submodules:
```bash
git clone --recurse-submodules https://github.com/henri14871/asure-open-solutions.git
```

If you already cloned:
```bash
git submodule update --init --recursive
```

## Working on an app (submodule)
```bash
cd apps/asure-flow
git checkout main
git pull
```

To pull the latest app commits from the parent repo:
```bash
git submodule update --remote --merge
```

## Contributing
PRs welcome. If you're adding a new app, prefer adding it as a submodule under `apps/`.
