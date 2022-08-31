Tackle2 Actions
===============

This is home to the common GitHub Actions and GitHub Workflows for Tackle. The
purpose is to encourage code re-use by centrally locating that which doesn't
belong to any specific project.

## Example Usage

```yaml
jobs:
  build-images:
    uses: konveyor/tackle2-actions/workflows/publish-images.yml@main
    with:
      registry: quay.io
      image_name: ${{ github.repository }}-container
    secrets: inherit
```
## Code of Conduct

Refer to Konveyor's Code of Conduct
[here](https://github.com/konveyor/community/blob/main/CODE_OF_CONDUCT.md).
