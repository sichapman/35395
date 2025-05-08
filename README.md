# 35395

## Current behavior

Renovate gives a generic error message - "Error updating branch: update failure"

## Expected behavior

Renovate updates the package name and version with no error

## Workaround

Prefix the `replacementVersion` with `==`. It then creates a PR : https://github.com/sichapman/35395/pull/1

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/35395
