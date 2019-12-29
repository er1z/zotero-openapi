# zotero-openapi
OpenAPI definitions for the Zotero API

Based on the Swagger definition https://zuphilip.github.io/swagger-ui/test/specs/zotero.yaml

## Generate Dart code
```
openapi-generator generate -i zotero-openapi/zotero.yaml -g dart -o zotero-dart
```