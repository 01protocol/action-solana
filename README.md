# Solana and Anchor action

Install the `solana` and `anchor` toolchains.

## Example

```yaml
on:
  push:
    branches: master
  pull_request:
    branches: master

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: 01protocol/action-solana@v1
        with:
          solana-version: 1.9.1
          anchor-version: 0.20.1
```
