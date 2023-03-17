# npm-install

A Github Actions composite action to install and cache node modules.

## Usage

```yaml
jobs:
    build:
        runs-on: 'ubuntu-latest'
        steps:
            - uses: 'actions/checkout@v3'
            - uses: 'dudeofawesome/npm-install@v1'
```

## Inputs

-   `package-path`: Path of dir with package.json.
-   `modules-dir`: Path of node_modules dir.
-   `cache-key` The cache key.
