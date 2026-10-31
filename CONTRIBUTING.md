# Contributing

Thanks for your interest in contributing! Contributions are welcome, whether it's
a bug report, a feature request, or a pull request.

## Getting Started

1. Fork the repository and clone it locally.
2. Open the package/project in Xcode (see README for requirements and supported
   Swift/iOS versions).
3. Build the project and run the test suite to make sure everything works before
   making changes.

## Reporting Issues

- Search existing issues first to avoid duplicates.
- Include a clear description, steps to reproduce, expected vs. actual behavior,
  and relevant environment details (Xcode version, Swift version, iOS version,
  device/simulator).
- Include a minimal reproducible example where possible.

## Submitting Changes

1. Create a new branch from `main` for your change:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Make your changes, following the existing code style and conventions.
3. Add or update tests to cover your changes.
4. Ensure all tests pass and the project builds without warnings.
5. Update documentation (README, code comments, etc.) as needed.
6. Commit your changes with a clear, descriptive commit message.
7. Push your branch and open a pull request against `main`.

## Pull Request Guidelines

- Keep PRs focused on a single change or feature.
- Describe what the PR does and why.
- Link any related issues.
- Be responsive to review feedback.
- Ensure CI checks pass before requesting review.

## Code Style

- Follow Swift API design guidelines: https://www.swift.org/documentation/api-design-guidelines/
- Keep code formatted consistently (e.g., via SwiftLint/SwiftFormat if configured
  in this repo).
- Write clear, self-documenting code; add comments only where intent isn't obvious.

## Testing

- All new functionality should include unit tests.
- Bug fixes should include a regression test where practical.
- Run the full test suite locally before submitting a PR.

## Code of Conduct

By participating in this project, you agree to abide by its Code of Conduct (see
`CODE_OF_CONDUCT.md` if present, or standard open-source community guidelines).

## License

By contributing, you agree that your contributions will be licensed under the
same license as this project (see `LICENSE`).
```
