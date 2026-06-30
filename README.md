# github-forward-pr-sample

This sample repository demonstrates a GitHub Actions workflow that automatically creates a pull request from `develop` to `staging` whenever a pull request is merged into `develop`.

## Branch flow

- Feature branches merge into `develop`
- The workflow creates or refreshes a follow-up PR from `develop` to `staging`
