# Contributing to Bouffalo Lab Projects

Thank you for your interest in Bouffalo Lab projects. This guide applies to every repository in the [bouffalolab](https://github.com/bouffalolab) organization that does not provide its own `CONTRIBUTING.md`.

By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Before You Post

1. Search the existing [discussions](https://github.com/bouffalolab/bouffalo_sdk/discussions) and issues, both open and closed. Your problem may already be answered.
2. Read the documentation:
   - [BouffaloSDK documentation](https://bl-mcu-sdk.readthedocs.io/zh-cn/latest/)
   - [Chip datasheets and reference manuals](https://github.com/bouffalolab/bl_docs)
3. Try the latest release or the default branch. The problem may already be fixed.

## Where to Post

| You want to | Post in |
|---|---|
| Ask how to use a chip, SDK, or tool | BouffaloSDK Discussions, [Q&A / Technical Support](https://github.com/bouffalolab/bouffalo_sdk/discussions/categories/q-a-technical-support) category, even if your question is about another Bouffalo Lab repository |
| Share an idea or feedback | BouffaloSDK Discussions, [Ideas & Feedback](https://github.com/bouffalolab/bouffalo_sdk/discussions/categories/ideas-feedback) category, where others can vote on it. For repositories without Discussions, use the **Feature request** issue form. |
| Show a project you built | BouffaloSDK Discussions, [Show and Tell](https://github.com/bouffalolab/bouffalo_sdk/discussions/categories/show-and-tell) category |
| Report a bug | An issue in the affected repository, using the **Bug report** form |

Issues and discussions start from forms, and blank issues are disabled, so that each post contains the information needed to act on it.

Business inquiries such as pricing, samples, or purchasing are not handled on GitHub. Please use the [Bouffalo Lab contact page](https://en.bouffalolab.com/contact/).

## Writing a Good Question or Bug Report

Include:

- **Chip and board or module**, for example BL616 on a BL616 DK board
- **Version**: a release tag or commit hash (`git describe --tags` or `git rev-parse HEAD`)
- **Environment**: host OS and toolchain version (`riscv64-unknown-elf-gcc --version`)
- **Steps to reproduce**, ideally with a minimal example
- **Complete logs as text** in a code block. Screenshots of logs cannot be searched or copied.
- **What you have already tried**

Please also:

- Post one problem per issue or discussion, and do not post the same problem in several places.
- Write in English if you can, so that more people can benefit. Chinese is also welcome.
- Never post confidential information. Issues and discussions are public: do not share documents under NDA, credentials, private keys, or customer data.

## Reporting Security Vulnerabilities

Do not report security vulnerabilities in public issues. Contact us through the [Bouffalo Lab contact page](https://en.bouffalolab.com/contact/) instead.

## Pull Requests

### How we develop

Most Bouffalo Lab repositories are developed in internal systems and published to GitHub with each release. The default branch on GitHub may therefore lag behind our internal codebase, and we may already be working on the change you have in mind.

### Talk to us first

For anything beyond a small fix, open an issue to discuss the idea before you write the code. This can save you effort if the change is already planned or does not fit the project's direction.

### Prepare your change

- Fork the repository and create a branch from the latest default branch.
- Keep each pull request focused on one logical change.
- Follow the coding style of the surrounding code. If the repository has a `.clang-format` file, format your changes with it.
- Fill in the pull request template: what the change does, why it is needed, and which chip and board you tested it on.

### Review and release

A Bouffalo Lab engineer reviews your pull request on GitHub and may ask for changes. Accepted changes are integrated into our internal codebase and ship in a subsequent release. Depending on the repository, the pull request is either merged on GitHub or closed with a note pointing to the release that contains it. Integration and regression testing can take time, so please be patient.

### Licensing

By submitting a pull request, you confirm that you have the right to submit the contribution, and you agree that it is licensed under the license of the target repository, for example Apache-2.0 for [bouffalo_sdk](https://github.com/bouffalolab/bouffalo_sdk).
