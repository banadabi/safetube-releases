# Contributing to SafeTube Releases

Thank you for your interest in SafeTube!

## Purpose of This Repository

This repository is specifically for:
- Hosting binary releases of SafeTube
- Tracking version history and changelogs
- Providing download links for end users

## Reporting Issues

### Before Creating an Issue

1. Check if the issue already exists in the [Issues](../../issues) section
2. Make sure you're using the latest version from the [Releases](../../releases) page
3. Gather relevant information (OS, version, error messages, steps to reproduce)

### Creating an Issue

When reporting a bug or problem:

1. Use a clear and descriptive title
2. Provide detailed steps to reproduce the issue
3. Include your system information:
   - Operating System and version
   - SafeTube version
   - Any error messages or screenshots

### Feature Requests

We welcome feature suggestions! When submitting a feature request:

1. Check if it's already been suggested
2. Clearly describe the feature and its use case
3. Explain how it would benefit SafeTube users

## Release Process

This section is for maintainers.

### Creating a New Release

1. Update `CHANGELOG.md` with all changes since the last release
2. Tag the release with semantic versioning (e.g., `v1.2.3`)
3. Use the `.github/RELEASE_TEMPLATE.md` as a guide for the release notes
4. Upload compiled binaries for all supported platforms
5. Include a `checksums.txt` file with SHA256 hashes

### Versioning

SafeTube follows [Semantic Versioning](https://semver.org/):
- **MAJOR** version for incompatible API changes
- **MINOR** version for backwards-compatible functionality additions
- **PATCH** version for backwards-compatible bug fixes

## Code of Conduct

Be respectful and constructive in all interactions. We aim to maintain a welcoming community for all users and contributors.

## Questions?

If you have questions that aren't covered here, feel free to open a discussion or issue.
