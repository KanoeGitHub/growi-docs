# Environment Variables

## Setting File

* `config/env.dev.js`

## Environment Variables Only Avaiable in Development

|Enviroment Variable|Description|
|---|---|
| **Option** ||
|`PLUGIN_NAMES_TOBE_LOADED`|Specify plugins to load for development. See [Plugins](/en/dev/plugin/architecture.md).|
|`DEV_HTTPS`|Start HTTPS express server using self-signed certificate in `resource/certs/localhost`.|
|`PUBLISH_OPEN_API`| Publish GROWI OpenAPI resources with [ReDoc](https://github.com/Rebilly/ReDoc). Visit `/api-docs`.|