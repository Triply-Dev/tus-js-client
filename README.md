# @triply/tus-js-client

A fork of the [tus-js-client](https://github.com/tus/tus-js-client) library, modified for TriplyDB.

### Changes that we've made
- The `onSuccess` event now returns the JSON body of the final `PATCH` request. This contains job data, including all files that are uploaded at that point in time.
- A `mapUrl` function was added as an Upload option. It's used to change URL's from console to api.

### Other
A complete list of changes can be found in the source code diff between the master and staging branches: [diff](https://github.com/tus/tus-js-client/compare/master...Triply-Dev:staging).

Please see [this link](https://github.com/tus/tus-js-client/blob/master/README.md) for the original TUS client readme.
