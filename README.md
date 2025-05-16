# @pnpm/trusted-deps

> A list of OSS packages that are known to require lifecycle scripts to function properly

We currently use the list maintained by Bun. So if you'd like to add a new package, submit it [here](https://github.com/oven-sh/bun/blob/main/src/install/default-trusted-dependencies.txt).

## Installation

```
pnpm add --config @pnpm/trusted-deps
```

## Usage

Reference `allow.json` from this config dependency in your `pnpm-workspace.yaml`:

```yaml
onlyBuiltDependenciesFile: node_modules/.pnpm-config/@pnpm/trusted-deps/allow.json
```

## License

MIT
