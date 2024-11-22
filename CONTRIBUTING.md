# Contribution Guide

## Clone the repo

- Following the open-source contributing practice, our team recommends using [github forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks) to make changes and publish to SRE managed repos
    - [Configuring fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/configuring-a-remote-repository-for-a-fork)
- Also, checkout our SRE workflow documentation [gitops](../../services/platform-education/gitops.md) workflow documentation

## Submit Pull request

- [GitHub documentation to create PR from fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

## Conventional Commits

- Our team recommends using [conventional commit messages](https://www.conventionalcommits.org/en/v1.0.0/)
- [Conventional Commits cheatsheet](https://cheatography.com/albelop/cheat-sheets/conventional-commits/)

### Commit message structure

```sh

<type>[optional scope]: <description>

[optional body]

[optional footer]
```

### Conventional Commit Example

```sh
feat(ci): enable mkdocs integration
