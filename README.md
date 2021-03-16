# **WARNING - This is a public repo used to host a custom action for GitHub workflows. Do not include proprietary or sensitive data.**

# actions-build-branch-info
Return the active build branch names

## Inputs

### `exclude-master`

Set true to exclude returning the master branch ex: for jobs like ios-democ-test

## Outputs

### `branches-json`

Build branch names in a JSON list

## Example usage

```yaml
uses: onshape/actions-build-branch-info@v1
```
