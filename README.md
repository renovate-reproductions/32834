# Custom package name for Hex dependency #32834

## Current behavior

With a dependency set as: `{:gun, "~> 2.0.0", hex: :grpc_gun}` renovate deals with `gun` versioning instead of `grpc_gun`

## Expected behavior

When `hex: :diff_name` option is present, renovate should do versioning of `diff_name` instead of `dep_name`

## Link to the Renovate issue or Discussion

[Put your link to the Renovate issue or Discussion here.](https://github.com/renovatebot/renovate/discussions/32834)
