# Contributing to DataRealm Humanoid Application Lab Projects

Thank you for your interest in contributing to the **DataRealm Humanoid Application Lab** (`HumanoidAppLab`)! We are building software that connects humanoid robotics to the industrial world, and we welcome contributions from engineers, researchers, roboticists, and open-source enthusiasts.

By contributing to any repository under the `HumanoidAppLab` organization, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## Table of Contents

- [Contributing to DataRealm Humanoid Application Lab Projects](#contributing-to-datarealm-humanoid-application-lab-projects)
  - [Table of Contents](#table-of-contents)
  - [Code of Conduct](#code-of-conduct)
  - [How Can I Contribute?](#how-can-i-contribute)
    - [Reporting Bugs](#reporting-bugs)
    - [Suggesting Enhancements](#suggesting-enhancements)
    - [Working on Issues](#working-on-issues)
  - [Development Guidelines](#development-guidelines)
    - [Branch Naming](#branch-naming)
    - [Commit Messages](#commit-messages)
    - [Code Quality \& Testing](#code-quality--testing)
  - [Pull Request Process](#pull-request-process)
  - [Security Disclosures](#security-disclosures)
  - [Getting Help](#getting-help)

---

## Code of Conduct

All contributors and participants must adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please report any unacceptable behavior to [info@DataRealmInc.com](mailto:info@DataRealmInc.com).

---

## How Can I Contribute?

### Reporting Bugs

Before creating a bug report, please check existing issues to ensure the issue has not already been reported or resolved.

If you find a new bug, please file a report using our [Bug Report Issue Template](.github/ISSUE_TEMPLATE/bug_report.yml):
- Provide a clear, descriptive title.
- Describe the expected versus actual behavior.
- Include step-by-step reproduction instructions.
- Provide environment details (operating system, runtime/framework versions, robot platform or simulator details).
- Attach relevant log snippets, error traces, or screenshots.

> [!NOTE]
> If you have discovered a potential security vulnerability, please do **not** open a public issue. Follow our [Security Policy](SECURITY.md) instead.

### Suggesting Enhancements

We welcome proposals for new features, hardware interfaces, algorithms, and documentation improvements.

Please submit your proposal using our [Feature Request Template](.github/ISSUE_TEMPLATE/feature_request.yml):
- Explain the use case and the problem being solved.
- Provide a concrete description of the proposed solution or API design.
- Outline any alternative approaches you considered.

### Working on Issues

If you'd like to work on an existing issue:
1. Comment on the issue expressing your interest so work isn't duplicated.
2. Look for issues labeled `good first issue` or `help wanted` if you are new to the codebase.
3. Wait for confirmation or an assignment from maintainers if it is a major change.

---

## Development Guidelines

### Branch Naming

Create feature branches branching off the default branch (`main`). Use descriptive branch names with conventional prefixes:

- `feature/<short-description>` – New feature or capability
- `fix/<short-description>` – Bug fix
- `docs/<short-description>` – Documentation improvements
- `refactor/<short-description>` – Code cleanup with no functional changes
- `test/<short-description>` – Adding or improving tests
- `chore/<short-description>` – Tooling, dependencies, or maintenance

### Commit Messages

We encourage following the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```text
<type>(<scope>): <short summary>

[optional body explaining context and rationale]

[optional footer(s), e.g., Fixes #123]
```

**Common types:**
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect code meaning (white-space, formatting, etc.)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to build process, auxiliary tools, or libraries

### Code Quality & Testing

- **Testing**: Ensure all automated tests pass before opening a pull request. Add tests covering any new code or bug fixes.
- **Style & Linting**: Follow the coding style and linter rules defined in the repository (e.g., Black/Ruff for Python, Prettier/ESLint for JS/TS, clang-format for C++).
- **Documentation**: Update documentation, docstrings, and README files to reflect any API or behavioral changes.

---

## Pull Request Process

1. **Fork & Branch**: Fork the target repository and create your working branch.
2. **Commit**: Keep commits atomic and logically separated.
3. **Rebase**: Keep your branch up to date with the upstream `main` branch.
4. **Pull Request Template**: Fill out the [Pull Request Template](PULL_REQUEST_TEMPLATE.md) completely, describing the change, testing steps, and linking related issues (e.g., `Closes #42`).
5. **Review**: Address feedback promptly. Maintainers may suggest adjustments to align with project architecture and standards.
6. **CI Checks**: Ensure all Continuous Integration checks pass.

---

## Security Disclosures

Do not report security vulnerabilities through public issues or pull requests. Please refer to our [Security Policy](SECURITY.md) for instructions on coordinated vulnerability disclosure.

---

## Getting Help

If you have questions about using or contributing to our software, please review our [Support Resources](SUPPORT.md) or visit [HumanoidAppLab.com](https://HumanoidAppLab.com).
