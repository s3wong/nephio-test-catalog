# nephio-free5gc-upf

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nephio-free5gc-upf`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nephio-free5gc-upf`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nephio-free5gc-upf
kpt live apply nephio-free5gc-upf --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
