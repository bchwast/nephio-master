# kuard2

## Description
kuard deployment

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kuard2`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree kuard2`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init kuard2
kpt live apply kuard2 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
