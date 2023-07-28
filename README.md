# github-docs-27127

Reproduce the issue https://github.com/github/docs/pull/27127

There are two GitHub Actions workflows.

- [watch-started.yaml](.github/workflows/watch-started.yaml): action type is `started`
- [watch-starred.yaml](.github/workflows/watch-starred.yaml): action type is `starred`

Please star this repository, then the workflow `watch-started.yaml` is triggered but the workflow `watch-starred.yaml` isn't triggered.

## LICENSE

[MIT](LICENSE)
