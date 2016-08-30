[![Build Status](https://img.shields.io/travis/shinesolutions/swagger-aem.svg)](http://travis-ci.org/shinesolutions/swagger-aem)

Swagger AEM
-----------

Swagger AEM is a [Swagger](http://swagger.io/) specification for [Adobe Experience Manager (AEM)](http://www.adobe.com/au/marketing-cloud/enterprise-content-management.html) API.

This specification is used to generate client libraries (currently only Ruby and Java clients, more languages support to follow).

API Spec documentation: [Latest](https://shinesolutions.github.io/swagger-aem/latest/api/index.html)

Generated Client
----------------

| Language | Getting Started                                                                                                                                                                 | API Documentation                                                               |   |   |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|---|---|
| Ruby     | [README](https://github.com/shinesolutions/swagger-aem/blob/master/ruby/README.md) [CHANGELOG](https://github.com/shinesolutions/swagger-aem/blob/master/ruby/CHANGELOG.md)     | [Latest](https://shinesolutions.github.io/swagger-aem/latest/ruby/index.html)   |   |   |
| Python   | [README](https://github.com/shinesolutions/swagger-aem/blob/master/python/README.md) [CHANGELOG](https://github.com/shinesolutions/swagger-aem/blob/master/python/CHANGELOG.md) | [Latest](https://shinesolutions.github.io/swagger-aem/latest/python/index.html) |   |   |
| Java     | [README](https://github.com/shinesolutions/swagger-aem/blob/master/java/README.md) [CHANGELOG](https://github.com/shinesolutions/swagger-aem/blob/master/java/CHANGELOG.md)     | [Latest](https://shinesolutions.github.io/swagger-aem/latest/java/index.html)   |   |   |

Development
-----------

To run build targets using `swagger-codegen` in your path:

    make <target>

If you want to use a custom `swagger-codegen-cli.jar`:

    SWAGGER_CODEGEN_JAR=/path/to/swagger-codegen-cli.jar make <target>

Testing
-------

Unit tests are generated by `swagger-codegen` along with the client code.

Integration tests are part of Swagger AEM and require an AEM instance running on port 4502.
