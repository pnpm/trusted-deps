# @pnpm/trusted-deps

> A list of some OSS packages that are known to require lifecycle scripts to function properly

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
