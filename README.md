# Action SPA

GitHub Action for [SPinnaker Admin (SPA) tool](https://github.com/kekeniker/spa).

## Usage

```yaml
      - name: Create service account
        uses: kekeniker/action-spa@v1
        with:
          command: service-account create -o /tmp/sa.json
```

### Action Inputs

| Name | Description | Default |
| --- | --- | --- |
| `command` | Command to execute | - (Required) |  

## License

[MIT](LICENSE)
