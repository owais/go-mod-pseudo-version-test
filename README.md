
Running `go get -u github.com/go-pg/pg@2606290a6ba1e484f9` fetches a correct copy of the go-pg lib but the pseudo version is tagged with `v0.0.0-<pseudo-version>` instead of `v6.15.1-<pseudo-version>`. The build still uses the expected version but go.mod implies that the library does not have a stable release yet and is not go modules compatible.

