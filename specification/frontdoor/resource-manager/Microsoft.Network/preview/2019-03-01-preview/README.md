# Public Preview API specification for FrontDoor WebApplicationFirewall Azure Resource

This directory contains preview schema specifications for the new Front Door Web Application Firewall Azure Resource. The API will be added to support Front Door Web Application Firewall on Azure Resource Manager.

The base swagger document for new features in this preview: [webapplicationfirewall.json](./webapplicationfirewall.json)

## Overview
The Front Door Web Application Firewall ARM API supports CRUD functionality on one object in the resource schema:
`Frontdoorwebapplicationfirewall` specifies custom and managed rules for protecting applications using a `Frontdoor` resource. Each rule can be configured to allow or block traffic based on matching conditions with the client request. The customized conditions can include the remote address, geo-locations, URI contents, HTTP headers, and more. With managed rules, users can automatically protect against common attack patterns such as SQL injection or cross-site scripting without manually configuring rules.

## Generated object-model UML diagram
This diagram is generated from the swagger spec by "[`oav`](https://github.com/Azure/oav) `generate-uml`"
![Generated UML snapshot](./assets/webapplicationfirewall.svg)

## Swagger and JSON specification reference and tools
 * [OpenAPI specification v2.0 (aka Swagger 2.0)](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md)
 * [Swagger.io online editor](https://editor.swagger.io/)
