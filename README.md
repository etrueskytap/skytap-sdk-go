# Skytap GO SDK
## API

API package provides go based REST client.

## API Tests
You must provide configuration to run the tests. Copy the `api/testdata/config.json.sample` file to `api/testdata/config.json`, and fill out the required fields. Note the the tests were run against a template containing a single Ubuntu 14.04 server VM and a preconfigured NAT based VPN. Other configurations may cause spurious test errors.

    export GOPATH=`pwd`
    go get -t github.com/skytap/skytap-sdk-go/api
    cd api
    go test -v

## License
Apache 2.0; see [LICENSE](LICENSE) for details
