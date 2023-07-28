# github-docs-27127

Reproduce the issue https://github.com/github/docs/pull/27127

There are two GitHub Actions workflows.

- [watch-started.yaml](.github/workflows/watch-started.yaml): action type is `started`
- [watch-starred.yaml](.github/workflows/watch-starred.yaml): action type is `starred`

Please star this repository, then the workflow `watch-started.yaml` is triggered but the workflow `watch-starred.yaml` isn't triggered.

e.g. https://github.com/suzuki-shunsuke/github-docs-27127/actions/runs/5690690689

So the action type `starred` is wrong and the correct action type is `started`.

## LICENSE

[MIT](LICENSE)
