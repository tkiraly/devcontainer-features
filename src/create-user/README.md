
# Create User (create-user)

A to assert the configured user exists in the container

## Example Usage

```json
"features": {
    "ghcr.io/tkiraly/devcontainer-features/create-user:0": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| create | Create the user if it doesn't exist | boolean | true |
| addToSudo | If the user is newly created, add it to group sudo (if it exists) | boolean | true |
| installSudo | Install sudo if it is not yet installed | boolean | true |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/tkiraly/devcontainer-features/blob/main/src/create-user/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
