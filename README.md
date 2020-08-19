# EnhancedAppStoreConnectOpenAPI
An enhanced version of the App Store Connect OpenAPI Spec

## What

This repo contains an enhanced [OpenAPI](https://swagger.io/resources/open-api/) spec document for [Apple's App Store Connect API](https://developer.apple.com/documentation/appstoreconnectapi).  This document builds upon the original provided by Apple following their announcement of enhancements to the API at WWDC 2020.  (See [here](https://developer.apple.com/videos/play/wwdc2020/10651/) and [here](https://developer.apple.com/videos/play/wwdc2020/10004/))

This version of the enhanced spec currently targets v1.2 of Apple's App Store Connect.

## Why

The original spec document is very detailed and contains definitions for a myriad of API operations within App Store Connect.  However, *documentation* for these API operations is not contained within the spec.  Additionally, the Operation IDs for each operation are cryptic and not reader-friendly.  As a result, API clients generated using [automated tools](https://github.com/OpenAPITools/openapi-generator) are suboptimal and difficult to use.

This enhancement to the spec includes documentation taken directly from Apple's [official App Store Connect API documentation](https://developer.apple.com/documentation/appstoreconnectapi), and Operation IDs that more closely follow typical conventions for many programming languages, such as Java or Swift.  As a result, API clients can be generated with properly commented code, and viewing the OpenAPI spec documentation using [SwaggerUI](https://swagger.io/tools/swagger-ui/), [ReDoc](https://github.com/Redocly/redoc), or other tools is much easier.

## How

The spec document was updated using [Apicurio Studio](https://www.apicur.io/studio/), a fantastic web-based OpenAPI editor.  If you haven't made use of it, I highly recommend checking it out.

## Release Notes

### Version 1.2

An initial release targeting v1.2 of Apple's App Store Connect API.