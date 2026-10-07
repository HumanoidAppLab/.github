# HumanoidAppLab / .github

Welcome to the central `.github` configuration repository for the **[DataRealm Humanoid Application Lab](https://humanoidapplab.com)** (`@HumanoidAppLab`) organization.

GitHub uses this special repository to define organization-wide default community health files, issue templates, workflow templates, and the organization profile.

---

## What Is This Repository?

When an individual repository under the `@HumanoidAppLab` organization does not define its own version of a community health file (such as `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, or issue templates), GitHub automatically falls back to the defaults hosted in this repository.

### Repository Layout

```text
.github/
├── .github/
│   ├── DISCUSSION_TEMPLATE/        # Templates for GitHub Discussions
│   │   ├── ideas.md
│   │   └── q-and-a.md
│   ├── ISSUE_TEMPLATE/             # Standard GitHub Issue Forms & config
│   │   ├── bug_report.yml
│   │   ├── feature_request.yml
│   │   └── config.yml
│   ├── FUNDING.yml                 # Organization-wide sponsorship configuration
│   └── pull_request_template.md    # PR template fallback
├── profile/
│   └── README.md                   # Organization profile displayed on github.com/HumanoidAppLab
├── workflow-templates/             # Reusable starter workflows available across the org
│   ├── ci.yml                      # Starter continuous integration workflow
│   ├── ci.properties.json
│   ├── lint.yml                    # Starter linting & formatting workflow
│   └── lint.properties.json
├── CODE_OF_CONDUCT.md              # Contributor Covenant Code of Conduct v2.1
├── CONTRIBUTING.md                  # Organization-wide contribution guidelines
├── LICENSE                         # Repository license (MIT)
├── PULL_REQUEST_TEMPLATE.md        # Default pull request template
├── README.md                       # This documentation file
├── SECURITY.md                     # Organization security and vulnerability policy
└── SUPPORT.md                      # Community and technical support resources
```

---

## Community Health Files Summary

| File | Purpose | Inherited by Child Repos? |
| --- | --- | :---: |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Contributor Covenant v2.1 defining acceptable community standards and enforcement. | Yes |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Guidelines on how to report issues, follow commit conventions, and submit PRs. | Yes |
| [`SECURITY.md`](SECURITY.md) | Vulnerability disclosure instructions, response SLAs, and safe harbor policy. | Yes |
| [`SUPPORT.md`](SUPPORT.md) | Guidance on getting technical help, questions, and commercial inquiries. | Yes |
| [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) | Checklist and structured template displayed when opening pull requests. | Yes |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) | Structured YAML issue forms for bugs, feature requests, and issue chooser config. | Yes |
| [`.github/DISCUSSION_TEMPLATE/`](.github/DISCUSSION_TEMPLATE/) | Starter discussion forms for proposals and Q&A. | Yes |
| [`.github/FUNDING.yml`](.github/FUNDING.yml) | Default sponsorship channels across the organization. | Yes |
| [`profile/README.md`](profile/README.md) | Markdown profile rendered on the main organization overview page. | N/A (Org profile) |
| [`workflow-templates/`](workflow-templates/) | Starter actions available in the "Actions -> New workflow" catalog. | Org-wide Catalog |

---

## Overriding Defaults in Individual Repositories

Any repository under `@HumanoidAppLab` can override an organization-level default by adding its own version of the file locally (in its root, `.github/`, or `docs/` folder).

For example:
- To use custom issue templates in a specific project, add `.github/ISSUE_TEMPLATE/` to that specific repository.
- To define a specific security contact or version matrix, add `SECURITY.md` in that specific repository.

---

## Maintenance & Contributions

Changes to files in this repository affect all repositories across the organization. If you wish to propose updates to organization policies, templates, or profile content, please open a pull request against this repository following our [Contributing Guidelines](CONTRIBUTING.md).

For inquiries, visit [HumanoidAppLab.com](https://HumanoidAppLab.com).