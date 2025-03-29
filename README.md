# Development Containers

This repository is for the Development Container Specification. You can check out the spec on our website https://containers.dev/ too.

A development container allows you to use a container as a full-featured development environment. It can be used to run an application, to separate tools, libraries, or runtimes needed for working with a codebase, and more.

The Development Container Specification seeks to find ways to enrich existing formats with common development specific settings, tools, and configuration while still providing a simplified, un-orchestrated local development experience.

![Stages of container-based development, from development to deployment](images/dev-container-stages.png)

The first format in the specification, `devcontainer.json`, was born out of necessity. It is a structured JSON with Comments (jsonc) metadata format that tools can use to store any needed configuration or settings for a development environment.

We envision that this same structured data can be embedded in images and other formats – all while retaining a common object model for consistent processing. For example, some of this same metadata can be used by other tools to provide a similar development experience.

Beyond repeatable setup, these same development containers provide consistency to avoid environment specific problems across developers and centralized build and test automation services. You can check out the specification and learn more about the various tools that support it at https://containers.dev.

A GitHub Action and an Azure DevOps Task are available in [devcontainers/ci](https://github.com/devcontainers/ci) for running a repository's dev container in continuous integration (CI) builds. These can be used to build and test source code in a consistent environment, regardless of where the CI build is run.

### Spec content

You may review the specification in the [docs/specs folder](https://github.com/devcontainers/spec/tree/main/docs/specs) of this repo.

You may also review active proposals in the [proposals folder](https://github.com/devcontainers/spec/tree/main/proposals).

Images used in this repo will be contained in the [images folder](/images). The icon for the [dev container GitHub org](https://github.com/devcontainers) is from the [Fluent icon library](https://github.com/microsoft/fluentui-system-icons).

## Contributing and Feedback

If you are interested in contributing, please check out the [How to Contribute](contributing.md) document, open an issue, or [join our community Slack channel](https://aka.ms/dev-container-community).

Please report issues in the following repositories:

- Spec-maintained Features and Templates: [devcontainers/features](https://github.com/devcontainers/features), [devcontainers/templates](https://github.com/devcontainers/templates)
- CLI reference implementation and non-spec related feature requests: [devcontainers/cli](https://github.com/devcontainers/cli)
- GitHub Action and Azure DevOps Task: [devcontainers/ci](https://github.com/devcontainers/ci)

# License

License for this repository:

Copyright © Microsoft Corporation All rights reserved.<br />
Creative Commons Attribution 4.0 License (International): https://creativecommons.org/licenses/by/4.0/legalcode
