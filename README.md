# Usage

Inside your `.github/workflows/workflow.yml` file:

```yaml
steps:
- uses: actions/checkout@v3
- uses: BandarHL/theos-action
  with:
    # Whether to download swift toolchain files. When true, add swift support to Theos.
    # Default: false
    swifttoolchain: ''
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
