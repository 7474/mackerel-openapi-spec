# Mackerel OpenAPI Spec

[OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) of [Mackerel API]("https://mackerel.io/ja/api-docs/).

## Snipet

```sh
# C# Client
npm install
npm run openapi-generator -- generate \
   -i ./mackerel-api.yml \
   -g csharp-dotnet2 \
   -o ./mackerel/client \
   --api-package Koudenpa.Mackerel.Api
```
