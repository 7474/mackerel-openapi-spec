# Mackerel OpenAPI Spec

[OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) of [Mackerel API](https://mackerel.io/ja/api-docs/).

View on Swagger UI: https://7474.github.io/mackerel-openapi-spec/


## Edit

```sh
docker run -d -p 80:8080 -v $(pwd):/tmp -e SWAGGER_FILE=/tmp/mackerel-api.yml swaggerapi/swagger-editor
```
