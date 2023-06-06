# demoApp

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] demoApp`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree demoApp`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init demoApp
kpt live apply demoApp --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
