# openapi-validator-buildkite-plugin
An [Buildkite plugin](https://buildkite.com/docs/agent/v3/plugins) to validate openapi specification files.

## Example

```yml
steps:
  - label: ':buildkite: lint pipelines'
    plugins:
      - xiaket/openapi-validator
          files:
            - specs/*.yaml
```

## License

MIT (see [LICENSE](LICENSE))
