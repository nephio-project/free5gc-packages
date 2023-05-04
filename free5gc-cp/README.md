# free5gc-cp

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] free5gc-cp`

Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree free5gc-cp`

Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init free5gc-cp
kpt live apply free5gc-cp --reconcile-timeout=2m --output=table
```

Details: https://kpt.dev/reference/cli/live/
