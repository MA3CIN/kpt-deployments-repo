# new-package-v3

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] new-package-v3`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree new-package-v3`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init new-package-v3
kpt live apply new-package-v3 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
