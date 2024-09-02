# bunny-sdk

[![GitHub Release](https://img.shields.io/github/v/release/jlarmstrongiv/bunny-launcher-github-action)](https://github.com/jlarmstrongiv/bunny-launcher-github-action)

## Installation

```yml
steps:
  - uses: actions/checkout@v4
  - uses: actions/setup-node@v4
    with:
      node-version: lts
  - uses: jlarmstrongiv/bunny-launcher-github-action@latest
    with:
      accessKey: ${{ secrets.BUNNY_ACCESS_KEY }}
```

## Documentation

Please read the [docs](https://bunny-launcher.net/github-action/) for usage and examples.
