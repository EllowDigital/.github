# Contributing to EllowDigital projects

Thank you for helping improve an EllowDigital project. Each repository can have its own product, client, security and release requirements. Read that repository's README, license and local contribution guidance before making changes.

## Before you start

- Check the repository's current issues and pull requests to avoid duplicate effort.
- For substantial changes, open an issue or contact the maintainer to agree on the intended scope first.
- Confirm that the repository's license and project permissions allow your proposed contribution.
- Never include credentials, environment files, private customer data, patient information, financial records or confidential client material in a commit, issue, screenshot or pull request.

## Branch and pull-request workflow

1. Create a focused working branch from the repository's development branch, typically **dev**.
2. Keep each change scoped to one feature, fix or documentation task.
3. Run the checks documented by that repository and review the result locally.
4. Open a pull request targeting **dev** when that branch exists. Do not target **main** or **master** directly unless the repository's instructions or a maintainer explicitly requires it.
5. Explain the problem, the solution, relevant risks, and the checks you ran. Include screenshots for visible UI changes when useful and safe.
6. Address review feedback and wait for approval before merge.

If a repository uses a different documented release process, follow that repository's instructions. Maintainers should promote approved work from development to the production branch through a pull request.

## Quality expectations

- Prefer clear, maintainable code that fits the existing patterns.
- Add or update tests where the project has a relevant test setup.
- Update documentation when setup, configuration or behaviour changes.
- Check responsive layouts, keyboard navigation, forms and error states for UI changes.
- Validate external links, contact details, configuration names and deployment assumptions.
- Explain checks that could not be run instead of implying they passed.
- Never commit real secrets. Treat every browser-exposed configuration value as public.

## Review checklist

Before requesting review, confirm that:

- The change has a clear purpose and avoids unrelated edits.
- Relevant tests, linting, type checks or production builds have been run where available.
- No private data, credentials, generated clutter or unapproved assets are included.
- Documentation and configuration examples match the implementation.
- The pull request targets the correct branch and describes any deployment implications.

## Respect project ownership

A repository being public does not automatically make all code, branding, images, copy or client materials open source. Check its license and any applicable permissions before copying, redistributing or adapting material. Third-party dependencies remain subject to their own terms.

## Questions

Use the project's issue tracker for reproducible, non-sensitive technical problems, or see [SUPPORT.md](SUPPORT.md) for other support routes.
