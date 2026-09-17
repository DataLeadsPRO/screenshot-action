# DataLeads Screenshot (GitHub Action)

Capture a full-page screenshot of any URL through a real browser and return the image reference.

Calls the DataLeads API endpoint `POST /v1/screenshot` and writes the JSON response to `dataleads-result.json` plus the `result` output.

## Usage

```yaml
steps:
  - uses: DataLeadsPRO/screenshot-action@v1
    with:
      url: https://example.com
      api_key: ${{ secrets.DATALEADS_API_KEY }}
```

Get a client key at [data.dataleads.pro](https://data.dataleads.pro).

## License

MIT
