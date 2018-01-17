# wallet-test-resources
These are resources used to test implementations of the evolving blockcerts certificate standard and issuer conventions.

## Branches
`master` should be used in most cases. It hosts all the URLs on http://localhost:1234 and is up to date with current issuer & certificate standards

`android` is identical to master, but URLs are hosted at http://10.0.2.2:1234. This is the [emulator loopback URL](https://stackoverflow.com/questions/15708235/how-10-0-2-2-of-emulator-resolves-to-127-0-0-1-of-windows), since *localhost* points to the device itself rather than the hosting computer. And wiremock [doesn't do variables](https://stackoverflow.com/questions/36289085/wiremock-variable-substitution-in-json-response).
