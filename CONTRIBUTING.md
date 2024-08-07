# Contributing

Please ensure you have read the [Code of Conduct](./CODE_OF_CONDUCT.md) before making any contribution.

## How to contribute

### Issues

Add new issues:
- [For doubts or questions about the project](https://github.com/DevoInc/genesys-ui/issues/new?assignees=&labels=question&projects=&template=1-questions.yml).
- [Report bugs](https://github.com/DevoInc/devo-datasource/issues/new?assignees=&labels=bug%2Ctriage&projects=&template=bug-report.yml)
- [New features](https://github.com/DevoInc/devo-datasource/issues/new?assignees=&labels=question&projects=&template=questions.yml)

### Pull requests
Contributions are made by opening pull requests from a forked copy of the repo. See detailed instructions below.

- Create a fork from the project on [Github](https://github.com/DevoInc/devo-datasource).
- Clone the fork on your local machine.
- Add the original repository as remote `upstream`.
- Create a new `feat/` branch from `main`.
- Commit messages should follow the [conventional commits specification](https://www.conventionalcommits.org/en/v1.0.0/).
- Write or update documentation if needed.
- Make sure `npm run test` and `npm run lint` pass.
- Push your branch to your fork (`origin`).
- Open a pull request from your fork targeting the project's `main` branch.
- Wait for the pull request to be approved and merged and pull the changes from the `upstream` remote.