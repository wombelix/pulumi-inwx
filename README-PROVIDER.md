# INWX Resource Provider

The INWX Resource Provider allows registration and management of domains and their domain contact resources.

## Installing

This package is available for several languages/platforms:

### Node.js (JavaScript/TypeScript)

To use from JavaScript or TypeScript in Node.js, install using either `npm`:

```bash
npm install @wombelix/inwx
```

or `yarn`:

```bash
yarn add @wombelix/inwx
```

### Python

To use from Python, install using `pip`:

```bash
pip install pulumi_inwx
```

### Go

To use from Go, use `go get` to grab the latest version of the library:

```bash
go get github.com/wombelix/pulumi-inwx/sdk/go/...
```

### .NET

To use from .NET, install using `dotnet add package`:

```bash
dotnet add package Pulumi.Inwx
```

## Configuration

The following configuration points are available for the `inwx` provider:

- `inwx:username` - (Required) Login username of the api
- `inwx:password` - (Required) Login password of the api
- `inwx:api_url`  - (Optional) URL of the RPC API endpoint. Use https://api.domrobot.com/jsonrpc/ for production and https://api.ote.domrobot.com/jsonrpc/ for testing. Default: https://api.domrobot.com/jsonrpc/

## Reference

For detailed reference documentation, please visit [the Pulumi registry](https://www.pulumi.com/registry/packages/inwx/api-docs/).
