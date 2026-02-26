# Contributing to QPay SDK

Thanks for your interest in contributing!

## Getting Started

1. Fork the repository
2. Clone your fork
3. Create a feature branch: `git checkout -b feature/my-feature`
4. Make your changes
5. Run tests to make sure everything passes
6. Commit your changes
7. Push to your fork and open a Pull Request

## Development

Each SDK package has its own language-specific setup. Check the README of the package you want to contribute to.

### Running Tests

| Package | Command |
|---------|---------|
| qpay-go | `go test -v -race ./...` |
| qpay-js | `npm test` |
| qpay-py | `pytest` |
| qpay-php | `vendor/bin/phpunit` |
| qpay-ruby | `bundle exec rake` |
| qpay-dart | `dart test` |
| qpay-rust | `cargo test` |
| qpay-dotnet | `dotnet test` |
| qpay-java | `mvn test` |
| qpay-swift | `swift test` |

## Pull Request Guidelines

- Keep PRs focused on a single change
- Add tests for new features
- Make sure CI passes before requesting review
- Follow the existing code style

## Reporting Issues

Open an issue on the relevant package repository with:
- Description of the problem
- Steps to reproduce
- Expected vs actual behavior

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
