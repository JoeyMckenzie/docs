Create an API token limited to managing a single org and its resources. Tokens are valid for 20 years by default. We recommend using a shorter expiry if practical.

## Usage
~~~
flyctl tokens create org [flags]
~~~

## Options

~~~
  -x, --expiry duration   The duration that the token will be valid (default 175200h0m0s)
  -h, --help              help for org
  -j, --json              JSON output
  -n, --name string       Token name (default "Org deploy token")
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
      --debug                 Print additional logs and traces
      --verbose               Verbose output
~~~

## See Also

* [flyctl tokens create](/docs/flyctl/tokens-create/)	 - Create Fly.io API tokens

