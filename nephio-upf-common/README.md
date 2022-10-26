# nephio-upf-common

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nephio-upf-common`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nephio-upf-common`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nephio-upf-common
kpt live apply nephio-upf-common --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
