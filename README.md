# AJ Script Version Checker

Each script has its own `{resourceName}.txt` file containing its latest version number (e.g., `1.0.0`). Scripts fetch their file on restart and notify if an update is available.

## File Format

Each `.txt` file contains a single line with the version in `major.minor.patch` format:

```
1.0.0
```

## Adding a Script

Create `{resourceName}.txt` in this repo and push to `main`. The script's config must point to:

```
https://raw.githubusercontent.com/ayushabhinav-dev/aj_houserobbery_version/refs/heads/main/{name}.txt
```

Where `{name}` is replaced with the resource name at runtime.

## Current Scripts

| File | Version |
|------|---------|
| `aj_houserobbery.txt` | 1.0.0 |
