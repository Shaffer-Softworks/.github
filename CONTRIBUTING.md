# Contributing

Thanks for your interest in Shaffer Softworks projects.

## Where to contribute

Each repository has its own issue tracker and pull requests. Open issues and PRs on the **specific repo** you are working on — not on this `.github` repository unless you are changing org-wide docs.

Browse all projects: [github.com/orgs/Shaffer-Softworks/repositories](https://github.com/orgs/Shaffer-Softworks/repositories)

## Reporting bugs

1. Search existing issues in the target repo first.
2. Include Home Assistant version, integration version, and relevant logs when reporting HA integration bugs.
3. Describe expected vs. actual behavior and steps to reproduce.

## Pull requests

1. Fork the repository and create a feature branch from `main`.
2. Keep changes focused — one logical change per PR.
3. Match the existing code style in that repo.
4. Update README or docs if behavior changes.
5. Describe what changed and why in the PR description.

## Home Assistant integrations

Most custom components are installed via [HACS](https://hacs.xyz/). If you are adding a new integration:

- Follow [Home Assistant integration development](https://developers.home-assistant.io/docs/creating_integration_manifest/) conventions.
- Include a clear `manifest.json`, config flow where appropriate, and setup docs.
- Test against a current Home Assistant release when possible.

## Code of conduct

Be respectful and constructive. We are a small open-source effort — clear communication helps everyone.

## Questions

For setup help, open a GitHub Issue on the relevant repository with details about your environment. For security concerns, see [SECURITY.md](SECURITY.md).
