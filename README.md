# NPM Publish Dev GitHub Action

This action publishes an NPM package using the current version and appends the current timestamp and the commit SHA.
Requires `npm-token` as input to authenticate.
Optional inputs are `node-version` (default: `lts/*`), `access` (default: `null`) and `tag` (default: `dev`).

## Usage

Add `uses: remindgmbh/npm-publish-dev-action@[version]` to workflow steps.
