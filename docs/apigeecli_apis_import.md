## apigeecli apis import

Import a folder containing API proxy bundles

### Synopsis

Import a folder containing API proxy bundles

```
apigeecli apis import [flags]
```

### Options

```
  -c, --conn int        Number of connections (default 4)
  -f, --folder string   folder containing one or more API proxy bundles in a zip format.
  -h, --help            help for import
```

### Options inherited from parent commands

```
  -a, --account string   Path Service Account private key in JSON
      --default-token    Use Google default application credentials access token
      --disable-check    Disable check for newer versions
      --metadata-token   Metadata OAuth2 access token
      --no-output        Disable printing all statements to stdout
      --no-warnings      Disable printing warnings to stderr
  -o, --org string       Apigee organization name
      --print-output     Control printing of info log statements (default true)
  -r, --region string    Apigee control plane region name; default is https://apigee.googleapis.com
  -t, --token string     Google OAuth Token
```

### SEE ALSO

* [apigeecli apis](apigeecli_apis.md)	 - Manage Apigee API proxies in an org

###### Auto generated by spf13/cobra on 6-Mar-2024
