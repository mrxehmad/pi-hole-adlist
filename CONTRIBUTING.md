# Contributing to Pi-hole Adlist Collection

Thank you for your interest in contributing to the Pi-hole Adlist Collection! All contributions are welcome and appreciated.

## How Can I Contribute?

### Reporting Issues

- Report false positives (legitimate domains being blocked)
- Report domains that should be added to the lists
- Suggest new categories of ad/tracking lists
- Report documentation issues

### Adding New Domains

- Submit pull requests to add new tracking or ad domains
- Improve existing lists by removing false positives
- Add comments to explain the purpose of specific domains

### Improving Documentation

- Update README with clearer instructions
- Improve issue templates
- Add usage examples

## Getting Started

### Prerequisites

- Basic understanding of how Pi-hole works
- Knowledge of domain lists and ad blocking principles
- Git and GitHub familiarity

### Fork the Repository

1. Fork the repository on GitHub
2. Clone your fork locally
3. Create a feature branch for your work
4. Submit a pull request when ready

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md if needed with details of changes, particularly for new blocklist categories.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. Add your changes to the appropriate blocklist file
5. Make sure your changes follow the same format as the rest of the list (IP address followed by domain)
6. Test that the domains you're adding are indeed related to advertising or tracking

### Adding New Domains

When adding new domains to a list:

- Add them to the appropriate category file
- Ensure the format follows the existing pattern
- Optionally add a comment explaining the domain's purpose
- Place the new entries in alphabetical order if possible

### Format Guidelines

- Blocklist format: `0.0.0.0 domain.com` or `127.0.0.1 domain.com`
- Comments start with `#` and should be on their own line
- Wildcard formats using `||domain.com^` are also acceptable

## Style Guide

- Keep the list organized and well-structured
- Use consistent formatting
- Add comments for complex or less-obvious entries
- Ensure domain names are properly formatted

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the repository maintainers.

## Questions?

If you have questions about contributing, feel free to open an issue to discuss what you would like to contribute.

Thank you for your contributions!