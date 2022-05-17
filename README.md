<br />

<p align="center">
    <img src="order.png" alt="strip-markdown-html logo" height="140">
</p>

<br />

Order-by-json is a GitHub action to order object by property in a json file

## Example usage

```yaml
- name: Order objects by a given property from a json file 
  uses: aloisdg/order-by-json@v0.3
  with:
    pattern: './data/*.json'
    property: 'Abbreviation'
```

## Parameters

* `pattern` (mandatory): {String} Pattern to be matched (rely on [Glob](https://github.com/isaacs/node-glob))

* `property` (optional): {String} Property to use to sort a list of object

* `encoding` (optional): {String} The text encoding of the file. Default: `utf8`.

## License

MIT
