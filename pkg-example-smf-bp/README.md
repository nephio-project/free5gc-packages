# pkg-smf

## Description
example pkg for smf blueprint

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] pkg-smf`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree pkg-smf`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init pkg-smf
kpt live apply pkg-smf --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
