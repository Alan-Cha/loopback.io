---
lang: en
title: 'API docs: rest.restbindings'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.rest.restbindings.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [RestBindings](./rest.restbindings.md)

## RestBindings namespace

RestServer-specific bindings

<b>Signature:</b>

```typescript
export declare namespace RestBindings 
```

## Namespaces

|  Namespace | Description |
|  --- | --- |
|  [Http](./rest.restbindings.http.md) | Request-specific bindings |
|  [SequenceActions](./rest.restbindings.sequenceactions.md) | Bindings for potential actions that could be used in a sequence |

## Variables

|  Variable | Description |
|  --- | --- |
|  [API\_SPEC](./rest.restbindings.api_spec.md) | Binding key for setting and injecting an OpenAPI spec |
|  [BASE\_PATH](./rest.restbindings.base_path.md) | Internal binding key for basePath |
|  [BIND\_ELEMENT](./rest.restbindings.bind_element.md) | Binding key for setting and injecting a wrapper function for setting values on a given context |
|  [CONFIG](./rest.restbindings.config.md) | Binding key for setting and injecting RestComponentConfig |
|  [ERROR\_WRITER\_OPTIONS](./rest.restbindings.error_writer_options.md) | Binding key for setting and injecting Reject action's error handling options.<!-- -->See https://github.com/strongloop/strong-error-handler\#options for the list of available options. Please note that the flag <code>log</code> is not used by <code>@loopback/rest</code>. |
|  [GET\_FROM\_CONTEXT](./rest.restbindings.get_from_context.md) | Binding key for setting and injecting a wrapper function for retrieving values from a given context |
|  [HANDLER](./rest.restbindings.handler.md) | Internal binding key for http-handler |
|  [HOST](./rest.restbindings.host.md) | Binding key for setting and injecting the host name of RestServer |
|  [HTTPS\_OPTIONS](./rest.restbindings.https_options.md) | Binding key for HTTPS options |
|  [PATH](./rest.restbindings.path.md) | Binding key for setting and injecting the socket path of the RestServer |
|  [PORT](./rest.restbindings.port.md) | Binding key for setting and injecting the port number of RestServer |
|  [PROTOCOL](./rest.restbindings.protocol.md) | Binding key for setting and injecting the protocol of RestServer |
|  [REQUEST\_BODY\_PARSER\_JSON](./rest.restbindings.request_body_parser_json.md) | Binding key for request json body parser |
|  [REQUEST\_BODY\_PARSER\_OPTIONS](./rest.restbindings.request_body_parser_options.md) | Binding key for request body parser options |
|  [REQUEST\_BODY\_PARSER\_RAW](./rest.restbindings.request_body_parser_raw.md) | Binding key for request raw body parser |
|  [REQUEST\_BODY\_PARSER\_STREAM](./rest.restbindings.request_body_parser_stream.md) | Binding key for request raw body parser |
|  [REQUEST\_BODY\_PARSER\_TEXT](./rest.restbindings.request_body_parser_text.md) | Binding key for request text body parser |
|  [REQUEST\_BODY\_PARSER\_URLENCODED](./rest.restbindings.request_body_parser_urlencoded.md) | Binding key for request urlencoded body parser |
|  [REQUEST\_BODY\_PARSER](./rest.restbindings.request_body_parser.md) | Binding key for request body parser |
|  [ROUTER\_OPTIONS](./rest.restbindings.router_options.md) |  |
|  [ROUTER](./rest.restbindings.router.md) | Internal binding key for rest router |
|  [SEQUENCE](./rest.restbindings.sequence.md) | Binding key for setting and injecting a Sequence |
|  [SERVER](./rest.restbindings.server.md) | Binding key for the server itself |
|  [URL](./rest.restbindings.url.md) | Binding key for setting and injecting the URL of RestServer |


