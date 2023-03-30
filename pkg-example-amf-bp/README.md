# pkg-amf

## Description
example pkg for amf blueprint

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] pkg-amf`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree pkg-amf`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init pkg-amf
kpt live apply pkg-amf --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
