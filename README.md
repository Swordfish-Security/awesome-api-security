# API Security Awesome

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)


![](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/api-security-pillars.png)

![](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/api-security-pillars-all.png)
Source: https://42crunch.com/6-pillars-of-api-security/
![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)
## API Design

### OpenAPI Documentation

| Tool                     | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github                           | License |
| ------------------------ | ------------------- | --------- | ----------- | -------------------------------- | ------- |
| ESDocs                   |                     |           |             |                                  |         |
| OpenAPI Generator Online |                     |           |             |                                  |         |
| redoc                    |                     |           |             | https://github.com/Redocly/redoc |         |
| TypeDocs                 |                     |           |             |                                  |         |
|                          |                     |           |             |                                  |         |

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)

## API Inventory

### API from APK file

| Tool     | Description                     | Swagger (formely OpenAPI 2.0) | OpenAPI 3.0.* | OpenAPI 3.1.* | Github                               | License            |
| -------- | ------------------------------- | ----------------------------- | ------------- | ------------- | ------------------------------------ | ------------------ |
| APKLeaks | Finding paths, secrets from apk | +                             | +             | +             | https://github.com/wireghoul/graudit | Apache-2.0 license |

### API from Code

| Tool          | Description                               | Swagger (formely OpenAPI 2.0) | OpenAPI 3.0.* | OpenAPI 3.1.* | Github                                      | License          |
| ------------- | ----------------------------------------- | ----------------------------- | ------------- | ------------- | ------------------------------------------- | ---------------- |
| graudit       | Finding paths, XSS, secrets by your rules | +                             | +             | +             | https://github.com/wireghoul/graudit        | GPL-3.0 license  |
| noir          | Identifies endpoints by static analysis   | +                             | +             | +             | https://github.com/noir-cr/noir             | MIT license      |
| sonar-openapi | SonarQube plugin                          |                               | +             | +             | https://github.com/apiaddicts/sonar-openapi | LGPL-3.0 license |

### API from HTTP

| Tool                     | Description                             | Swagger (formely OpenAPI 2.0) | OpenAPI 3.0.* | OpenAPI 3.1.* | Github                                          | License          |
| ------------------------ | --------------------------------------- | ----------------------------- | ------------- | ------------- | ----------------------------------------------- | ---------------- |
| akto                     |                                         |                               |               |               |                                                 |                  |
| metlo                    |                                         |                               |               |               |                                                 |                  |
| mitmproxy + mitm2swagger |                                         | +                             | +             | +             | https://github.com/wireghoul/graudit            | GPL-3.0 license  |
| AutoSpec                 | Identifies endpoints by static analysis | +                             | +             | +             | https://github.com/Adawg4/openapi-autospec      | MIT license      |
| OpenAPI DevTools         |                                         |                               |               |               | https://github.com/AndrewWalsh/openapi-devtools | LGPL-3.0 license |

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)
## API Development

### OpenAPI Parsers 

| Tool           | Swagger (formely OpenAPI 2.0) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                                                      | License     |
| -------------- | ----------------------------- | ------------- | ------------- | --------------------------------------------------------------------------- | ----------- |
| kin-openapi    | +                             | +             | +             | https://github.com/getkin/kin-openapi                                       | MIT license |
| libopenapi     | +                             | +             | +             | https://github.com/pb33f/libopenapi<br>https://pb33f.io/libopenapi/openapi/ | MIT License |
| swagger-parser |                               |               |               | https://github.com/APIDevTools/swagger-parser                               | MIT license |

### OpenAPI Converters

| Tool                                | Класс           | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                                                                                                                 | License |
| ----------------------------------- | --------------- | ------------------- | ------------- | ------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| API-Flow                            | many            |                     |               |               | https://github.com/luckymarmot/API-Flow                                                                                                |         |
| api-spec-converter                  | swagger/swagger |                     |               |               | 1. [https://lucybot-inc.github.io/api-spec-converter/](https://lucybot-inc.github.io/api-spec-converter/)<br>2. local from github repo |         |
| api-spec-converter                  | many            |                     |               |               | https://github.com/LucyBot-Inc/api-spec-converter                                                                                      |         |
| apimatic                            | many            |                     |               |               | https://www.apimatic.io/                                                                                                               |         |
| at-your-service                     | network/openapi |                     |               |               | https://github.com/AndrewWalsh/at-your-service                                                                                         |         |
| avantation                          | har/openapi     |                     |               |               | https://github.com/anbuksv/avantation                                                                                                  |         |
| converter-yaml-to-jsson             |                 |                     |               |               | https://onlineyamltools.com/convert-yaml-to-json                                                                                       |         |
| cURLtoSwagger                       | curl/openapi    |                     |               |               | https://github.com/goofmint/cURLtoSwagger                                                                                              |         |
| har2openapi                         | har/openapi     |                     |               |               | https://github.com/dcarr178/har2openapi                                                                                                |         |
| har2openapi                         | har/openapi     |                     |               |               | https://github.com/dcarr178/har2openapi                                                                                                |         |
| json-schema-to-openapi-schema       | json/openapi    |                     |               |               | https://github.com/wework/json-schema-to-openapi-schema                                                                                |         |
| kin-openapi                         |                 |                     |               |               |                                                                                                                                        |         |
| mitmproxy2swagger                   | mitm/swagger    |                     |               |               | [https://github.com/alufers/mitmproxy2swagger](https://github.com/alufers/mitmproxy2swagger)                                           |         |
| oas-kit                             | swagger/openapi |                     |               |               | https://github.com/Mermade/oas-kit                                                                                                     |         |
| openapi-schema-to-json-schemaPublic | openapi/json    |                     |               |               | https://github.com/mikunn/openapi-schema-to-json-schema                                                                                |         |
| openapi-to-postman                  | postman/openapi |                     |               |               |                                                                                                                                        |         |
| postman-to-openapi                  | postman/openapi |                     |               |               | https://github.com/joolfe/postman-to-openapi                                                                                           |         |
| postman2openapi                     | postman/openapi |                     |               |               | [https://kevinswiber.github.io/postman2openapi/](https://kevinswiber.github.io/postman2openapi/)                                       |         |
| postman2openapi                     | postman/openapi |                     |               |               | https://github.com/kevinswiber/postman2openapi                                                                                         |         |
| swagger2openapi                     | swagger/openapi |                     |               |               | https://github.com/APIs-guru/swagger2openapi                                                                                           |         |


### OpenAPI Linters

| Tool                       | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                                    | License            |
| -------------------------- | ------------------- | ------------- | ------------- | --------------------------------------------------------- | ------------------ |
| APICheck                   |                     |               |               |                                                           |                    |
| https://ratemyopenapi.com/ |                     |               |               |                                                           |                    |
| kin-openapi                |                     |               |               |                                                           |                    |
| OpenAPI v3 Linter          | +                   | +             | +             | https://bbva.github.io/apicheck/tools/edge/openapiv3-lint |                    |
| openapi-linter             |                     |               |               | https://github.com/superfaceai/openapi-linter             |                    |
| openapi-spec-validator     |                     |               |               | https://github.com/python-openapi/openapi-spec-validator  |                    |
| optic                      |                     |               |               | https://github.com/opticdev/optic                         |                    |
| redocly-cli                |                     |               |               | https://github.com/Redocly/redocly-cli                    |                    |
| speccy                     | +                   | +             | not info      | https://github.com/wework/speccy                          | MIT license        |
| spectral-lint              |                     |               |               | https://github.com/stoplightio/spectral                   | Apache-2.0 license |
| super-linter               | +                   | +             | +             | https://github.com/super-linter/super-linter              |                    |
| swagger-parser             | +                   | +             | +             | https://github.com/APIDevTools/swagger-parser             | MIT license        |
| vacuum                     | +                   | +             | +             | https://github.com/daveshanley/vacuum                     | MIT license        |


### OpenAPI Differs

**Purpose**: Diff old and new spec

| Инструмент      | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                       | License            |
| --------------- | ------------------- | ------------- | ------------- | -------------------------------------------- | ------------------ |
| oasdiff         | +                   | +             | +             | https://github.com/Tufin/oasdiff             | Apache-2.0 license |
| openapi-changes | +                   | +             | +             | https://github.com/daveshanley/vacuum        | MIT license        |
| openapi-diff    | +                   | +             | +             | https://github.com/OpenAPITools/openapi-diff | Apache-2.0 license |


### OpenAPI Compliant and Validator

| Tool                   | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                                       | License                                | CI/CD |
| ---------------------- | ------------------- | ------------- | ------------- | ------------------------------------------------------------ | -------------------------------------- | ----- |
| APICheck Send to proxy | +                   | +             |               | https://bbva.github.io/apicheck/tools/apicheck/send-to-proxy |                                        |       |
| wiretap                | +                   | +             |               | https://github.com/pb33f/wiretap                             | GNU Affero General Public License v3.0 |       |

### OpenAPI Sensitive Data Checker

| Tool                    | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                                        | License | CI/CD |
| ----------------------- | ------------------- | ------------- | ------------- | ------------------------------------------------------------- | ------- | ----- |
| APICheck sensitive-data | +                   | +             |               | https://bbva.github.io/apicheck/tools/apicheck/sensitive-data |         |       |

### OpenAPI JWT Checker

| Tool                 | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                                     | License | CI/CD |
| -------------------- | ------------------- | ------------- | ------------- | ---------------------------------------------------------- | ------- | ----- |
| APICheck jwt-checker |                     |               |               | https://bbva.github.io/apicheck/tools/apicheck/jwt-checker |         |       |

### OpenAPI UUIDv1 Checker

| Tool        | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                                           | License | CI/CD |
| ----------- | ------------------- | ------------- | ------------- | ---------------------------------------------------------------- | ------- | ----- |
| GUID Reaper |                     |               |               | https://gist.github.com/DanaEpp/8c6803e542f094da5c4079622f9b4d18 |         |       |


![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)
## API Testing

### OpenAPI Tester

**Purpose**: Find OWASP top 10 vulns

| Tool                      | Swagger (OpenAPI 2) | OpenAPI 3.0.x | OpenAPI 3.1.x | Github                                               | License            | CI/CD |
| ------------------------- | ------------------- | ------------- | ------------- | ---------------------------------------------------- | ------------------ | ----- |
| Astra                     | +                   | +             | +             | https://github.com/flipkart-incubator/Astra          | Apache-2.0 license |       |
| Automatic API Attack Tool | +                   | +             | +             | https://github.com/imperva/automatic-api-attack-tool | MIT license        |       |
| cherrybomb                | +                   | +             | +             | https://github.com/blst-security/cherrybomb          | Apache-2.0 license | +     |
| dredd                     | +                   | expiremental  | -             |                                                      |                    |       |
| OWASP OFFAT               |                     |               |               | https://github.com/OWASP/OFFAT                       | MIT license        |       |
| OWASP ZAP                 |                     |               |               |                                                      |                    |       |
| sj (Swagger Jacker)       | +                   | +             | +             | https://github.com/BishopFox/sj                      | MIT license        | +     |


### OpenAPI Fuzzers

**Purpose**: Find unexpected errors (ex. 500x)

| Tool           | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github                                       | License          | CI/CD |
| -------------- | ------------------- | --------- | ----------- | -------------------------------------------- | ---------------- | ----- |
| APIFuzzer      |                     |           |             | https://github.com/KissPeter/APIFuzzer       |                  |       |
| CATS           |                     |           |             | https://github.com/Endava/cats               |                  |       |
| fuzz-lightyear |                     |           |             | https://github.com/Yelp/fuzz-lightyear       |                  |       |
| openapi-fuzzer | +                   | +         | +           | https://github.com/matusf/openapi-fuzzer     | AGPL-3.0 license |       |
| restler-fuzzer | +                   | +         | +           | https://github.com/microsoft/restler-fuzzer  |                  |       |
| schemathesis   | +                   | +         | +           | https://github.com/schemathesis/schemathesis |                  |       |
| EvoMaster      |                     |           |             | https://github.com/WebFuzzing/EvoMaster      |                  |       |
| fuzzapi        |                     |           |             | https://github.com/Fuzzapi/fuzzapi           |                  |       |

### API Load-Tester

**Purpose**: Find unexpected errors (ex. 500x)

| Tool        | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github                                | License | CI/CD |
| ----------- | ------------------- | --------- | ----------- | ------------------------------------- | ------- | ----- |
| k6.js       |                     |           |             | https://github.com/grafana/k6         |         |       |
| yandex-tank |                     |           |             | https://github.com/yandex/yandex-tank |         |       |
| jMeter      |                     |           |             |                                       |         |       |

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)

## API Protection

### API Firewall (OpenAPI Analyzer)

| Tool         | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github                                    | License            |
| ------------ | ------------------- | --------- | ----------- | ----------------------------------------- | ------------------ |
| apiclarity   |                     |           |             | https://github.com/openclarity/apiclarity | Apache-2.0 license |
| api-firewall | +                   | +         | +           | https://github.com/wallarm/api-firewall   | MPL-2.0 license    |


### API Gateway

| Tool          | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github                               | License            |
| ------------- | ------------------- | --------- | ----------- | ------------------------------------ | ------------------ |
| Apache APISIX | +                   | +         | +           | https://github.com/apache/apisix<br> | Apache-2.0 license |
>There are a lot of them...apisix looks decent, but not enough documentation.
### API WAF

| Tool    | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github | License  |
| ------- | ------------------- | --------- | ----------- | ------ | -------- |
| wallarm |                     |           |             | <br>   | Commerce |


![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)

## API Governance

### API Security Platform

**Purpose**: Detect API attacks in real time, some testing, some API - gateway.

| Tool  | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github                                    | License | CI/CD |
| ----- | ------------------- | --------- | ----------- | ----------------------------------------- | ------- | ----- |
| akto  | +                   | +         | +           | https://github.com/akto-api-security/akto |         |       |
| metlo | +                   | +         | +           | https://github.com/metlo-labs/metlo       |         |       |
### API Management Platform

**Purpose**: Develop API, Publish API, Detect API attacks in real time, API testing, API gateway, Monitor API, Control Access API.

| Tool             | Swagger (OpenAPI 2) | OpenAPI 3 | OpenAPI 3.1 | Github                               | License | CI/CD |
| ---------------- | ------------------- | --------- | ----------- | ------------------------------------ | ------- | ----- |
| Gravitee.io      | +                   | +         | +           | https://github.com/gravitee-io       |         |       |
| WSO2 API Manager | +                   | +         | +           | https://github.com/wso2/product-apim |         |       |

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)

## Contributions

Let's go

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)

## Resources

- https://danaepp.com
- https://apisyouwonthate.com/
- https://nordicapis.com/
- https://apisecurity.io/

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)

## Backlog

- [ ] A simple example of how to run tools
- [ ] Example of launch in the CI/CD
- [ ] Add tools for GraphQL, Blueprint etc. 
- [ ] Specify which vulnerabilities from OWASP can be closed

![-----------------------------------------------------](https://raw.githubusercontent.com/Swordfish-Security/awesome-api-security/main/assets/aqua-line.png)