## Source

https://github.com/juanfran/taiga-override-directive-example

## Install
```
mkdir -p taiga-front/dist/plugins
cd taiga-front/dist/plugins
git clone https://github.com/gmarton/taiga-ui-mods.git
```

Add to you conf.json in `taiga-front/dist/conf.json`

```json
"contribPlugins": [
    "/plugins/taiga-ui-mods/conf.json"
]
```

Loads main.css in your taiga instance.
