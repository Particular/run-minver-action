# run-minver-action

Installs and runs MinVer using the CLI and conventions of repos in the Particular org:

* MinVer settings may exist in `src/Custom.Build.props`

The version calculated by MinVer is written to the environment variable `MinVerVersion`, the same as if MinVer is run from the MSBuild task.

## Usage

Basic:

```yaml
    steps:
      - name: Run MinVer
        uses: Particular/run-minver-action@v1.0.0
```

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE.md).
