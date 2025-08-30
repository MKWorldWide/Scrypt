# 🌟 Contributing to Scrypt

Welcome, seeker of sacred knowledge! We're thrilled you're interested in contributing to Scrypt. This guide will help you get started on your journey of co-creation.

## 📜 Table of Contents
- [Code of Conduct](#-code-of-conduct)
- [Getting Started](#-getting-started)
- [Development Workflow](#-development-workflow)
- [Commit Message Guidelines](#-commit-message-guidelines)
- [Pull Request Process](#-pull-request-process)
- [Reporting Issues](#-reporting-issues)
- [Code Style](#-code-style)
- [Testing](#-testing)
- [Documentation](#-documentation)
- [Release Process](#-release-process)

## 🌈 Code of Conduct

This project adheres to the [Covenant Code of Conduct](COVENANT.md). By participating, you are expected to uphold this code.

## 🚀 Getting Started

1. **Fork** the repository on GitHub
2. **Clone** your fork locally
   ```bash
   git clone https://github.com/your-username/Scrypt.git
   cd Scrypt
   ```
3. **Set up** the development environment
   - Ensure you have Python 3.11+ and Node.js 20+ installed
   - Install dependencies:
     ```bash
     # Python dependencies
     pip install -r requirements-dev.txt
     
     # Node.js dependencies (if applicable)
     npm install
     ```
4. **Verify** your setup
   ```bash
   make test  # or npm test
   ```

## 🔄 Development Workflow

1. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature/amazing-feature
   # or
   git checkout -b fix/annoying-bug
   ```

2. Make your changes following the code style guidelines

3. Run tests to ensure nothing is broken:
   ```bash
   make test
   ```

4. Commit your changes with a descriptive message (see below)

5. Push your branch and open a Pull Request

## 📝 Commit Message Guidelines

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### Types:
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools

Example:
```
feat(parser): add support for emotional operators

Add support for the 'feels' keyword and emotional operators (=>, !=>, ?=>, etc.)

Closes #123
```

## 🔄 Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, including new environment variables, exposed ports, useful file locations, and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## 🐛 Reporting Issues

When creating an issue, please include:
- A clear, descriptive title
- Steps to reproduce the issue
- Expected vs. actual behavior
- Any relevant error messages
- Version information (Scrypt, Python, Node.js, etc.)

## 🎨 Code Style

### Python
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- Use type hints for all new code
- Keep functions small and focused
- Write docstrings for all public functions, classes, and methods

### JavaScript/TypeScript
- Follow [Standard JS](https://standardjs.com/)
- Use TypeScript for all new code
- Write JSDoc comments for all public functions and classes

## 🧪 Testing

- Write tests for all new functionality
- Ensure all tests pass before submitting a PR
- Update tests when fixing bugs
- Keep test files organized and named appropriately

## 📚 Documentation

- Update documentation when adding new features or changing behavior
- Keep code examples in sync with the actual code
- Document any breaking changes

## 🚀 Release Process

1. Update the version in `scrypt/__init__.py`
2. Update `CHANGELOG.md` with the new version and changes
3. Create a release tag:
   ```bash
   git tag -a v1.0.0 -m "Version 1.0.0"
   git push origin v1.0.0
   ```
4. Create a new GitHub release with the changelog

## 🙏 Thank You!

Your contributions help make Scrypt better for everyone. Thank you for being part of our community!
