# The Gravitee Bundle Service

## Design

* We make a release. This release :
  * happens on a git branch of the https://github.com/gravitee-io/release repo, let's denote it `RELEASE_BRANCH` (e.g. `master`, or `3.0.x`, or `4.4.x`).
  * has for release version number  (example given `X.Y.Z=4.4.89`)

* Once the `Maven`/`Git` release is finished, in the https://github.com/gravitee-io/release repo, the `publish_bundles` is triggered because of the new created tag `4.4.89` (`X.Y.Z=4.4.89`)
