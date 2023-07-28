# github-docs-27127

Reproduce the issue https://github.com/github/docs/issues/27129

There are two GitHub Actions workflows.

- [watch-started.yaml](.github/workflows/watch-started.yaml): activity type is `started`
- [watch-starred.yaml](.github/workflows/watch-starred.yaml): activity type is `starred`

Please star this repository, then the workflow `watch-started.yaml` is triggered but the workflow `watch-starred.yaml` isn't triggered.

e.g. https://github.com/suzuki-shunsuke/github-docs-27127/actions/runs/5690690689

So the activity type `starred` is wrong and the correct activity type is `started`.

## LICENSE

[MIT](LICENSE)
