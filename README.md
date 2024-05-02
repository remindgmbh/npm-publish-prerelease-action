# NPM Publish Prerelease GitHub Action

This action publishes an NPM package using the current version and appends the current timestamp and the commit SHA.
Requires `npm-token` as input to authenticate.
Optional inputs are `node-version` (default: `lts/*`) and `access` (default: `null`).

## Usage

Add `uses: remindgmbh/npm-publish-prerelease-action@[version]` to workflow steps.
