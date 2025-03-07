# Awesome Connect

A curated list of projects and resources in the Connect ecosystem.

Read our [contribution guidelines](CONTRIBUTING.md) if you wish to propose a change.

## Contents

- [General](#general)
- [Dart](#dart)
- [Go](#go)
- [Kotlin](#kotlin)
- [Swift](#swift)
- [TypeScript and JavaScript](#typescript-and-javascript)

## General

* [conformance](https://github.com/connectrpc/conformance) - Connect, gRPC, and gRPC-Web interoperability tests.
* [connectrpc.com](https://github.com/connectrpc/connectrpc.com) - The connectrpc.com website.
* [Connect-gRPC Envoy Bridge Demo](https://github.com/connectrpc/envoy-demo) - Demo of the [Connect-gRPC bridge](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/connect_grpc_bridge_filter) in Envoy.
* 📝 [Connect: A better gRPC](https://buf.build/blog/connect-a-better-grpc) - Connect launch blog post.
* 📝 [Connect RPC vs. Google gRPC](https://buf.build/blog/grpc-conformance-deep-dive) - Conformance test suite launch blog post.
* 📝 [Connect RPC joins CNCF](https://buf.build/blog/connect-rpc-joins-cncf) - Connect joins the CNCF announcement blog post.
* 🎥 [Hand-writing a gRPC Handler in 7 minutes](https://www.youtube.com/watch?v=rNI_pCa9slQ) - GopherCon 2022 lightning talk by Akshay Shah.

Third-party
* [Awesome gRPC](https://github.com/grpc-ecosystem/awesome-grpc) - List of gRPC projects that may be useful if you have configured your Connect clients to use the gRPC protocol.
* [buf curl](https://buf.build/docs/curl/usage/) - Invoke RPCs from the command line on a Connect, gRPC, or gRPC-Web server.
* [gRPC-Web Dev Tools](https://github.com/SafetyCulture/grpc-web-devtools) - Browser extension for debugging gRPC-Web and Connect network requests (Chrome and Firefox).

## Dart

* [Connect-Dart](https://github.com/connectrpc/connect-dart) - The Connect RPC runtime for Dart.

## Go

* [Connect-Go](https://github.com/connectrpc/connect-go) - The Connect RPC runtime for Go.
* [Connect-Go examples](https://github.com/connectrpc/examples-go) - An example RPC service built with Connect that is hosted at [https://connectrpc.com/demo/](https://connectrpc.com/demo/).
* [authn](https://github.com/connectrpc/authn-go) - Pluggable authentication for Connect servers.
* [cors](https://github.com/connectrpc/cors-go) - CORS support for Connect servers.
* [grpchealth](https://github.com/connectrpc/grpchealth-go) - gRPC compatible health checks for any net/http server — including those built with Connect.
* [grpcreflect](https://github.com/connectrpc/grpcreflect-go) - gRPC compatible server reflection API for any net/http server — including those built with Connect.
* [otelconnect](https://github.com/connectrpc/otelconnect-go) - [OpenTelemetry](https://opentelemetry.io/) tracing and metrics collection for Connect servers and clients.
* 📝 [OpenTelemetry for Connect-Go](https://buf.build/blog/connect-opentelemetry-go) - otelconnect-go launch blog post.
* [validate](https://github.com/connectrpc/validate-go) - A Connect interceptor for [protovalidate-go](https://github.com/bufbuild/protovalidate-go).
* [Vanguard](https://github.com/connectrpc/vanguard-go) - Transcode between any/all of gRPC, gRPC-Web, Connect, or REST.

Third-party
* [connectproto](https://github.com/akshayjshah/connectproto) - Customize the default JSON and binary codecs from [Connect-Go](https://github.com/connectrpc/connect-go).
* [fauxrpc](https://github.com/sudorandom/fauxrpc) - Generate fake implementations of gRPC, gRPC-Web, Connect, and REST services to assist in testing.

## Kotlin

* [Connect-Kotlin](https://github.com/connectrpc/connect-kotlin) - The Connect RPC runtime for Kotlin.
* 📝 [Announcing Connect-Kotlin](https://buf.build/blog/announcing-connect-kotlin) - Connect-Kotlin launch blog post.

## Swift

* [Connect-Swift](https://github.com/connectrpc/connect-swift) - The Connect RPC runtime for Swift.
* 📝 [Announcing Connect-Swift](https://buf.build/blog/announcing-connect-swift) - Connect-Swift launch blog post.

## TypeScript and JavaScript

* [Connect-ES](https://github.com/connectrpc/connect-es) - The Connect RPC runtime for TypeScript and JavaScript.
* [Connect-ES examples](https://github.com/connectrpc/examples-es) - Example projects using Connect-ES with various TypeScript web frameworks and tooling.
* [Connect Playwright](https://github.com/connectrpc/connect-playwright-es) - Utilities for writing [Playwright](https://playwright.dev) tests.
* [Connect Query](https://github.com/connectrpc/connect-query-es) - A wrapper around [TanStack Query](https://tanstack.com/query) for Connect. 
* 📝 [Introducing Connect Query](https://buf.build/blog/introducing-connect-query) - Connect Query launch blog post.
* 📝 [Connect RPC for JavaScript](https://buf.build/blog/connect-es-v2) - Connect-ES v2 launch blog post.
