# github-action-go-demo

This project demonstrates how to use [github action](https://docs.github.com/en/actions/guides) to build and publish go programs.

See [.github/workflows/release01.yml](./.github/workflows/release01.yml) for detail.

Trigger the action:

```bash {.line-numbers}
git tag v1.0.25 # or other version
git push --tags
```
