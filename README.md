# babel-plugin-react-jss

Automatically sets displayName for JSS-React components. Prefixed with "JSS_"


## Installation
Simply add `add-react-displayname` to your `.babelrc` file:

```json
{
    "plugins": ["add-react-jss"]
}
```

## Troubleshooting

#### Doesn't work for decorated classes

If you are using the `transform-decorators-legacy` plugin, make sure it's placed *after* this plugin in your plugin list.

## Testing

`npm test`
