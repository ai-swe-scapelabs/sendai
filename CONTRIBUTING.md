# Contributing to Sendai

Thank you for your interest in contributing to the Sendai project! This guide will help you get started with contributing to our codebase.

## 🤝 How to Contribute

### Reporting Bugs

If you find a bug, please:

1. **Check existing issues** to make sure it hasn't been reported
2. **Create a new issue** using the bug report template
3. **Provide detailed information**:
   - Steps to reproduce
   - Expected vs actual behavior
   - Environment details (OS, version, etc.)
   - Screenshots if applicable

### Suggesting Features

We welcome feature suggestions! To propose a new feature:

1. **Check existing issues** for similar requests
2. **Create a feature request** with:
   - Clear description of the feature
   - Use case and motivation
   - Possible implementation approach
   - Examples of how it would work

### Code Contributions

#### Getting Started

1. **Fork the repository**
   ```bash
   # Fork on GitHub, then clone your fork
   git clone https://github.com/YOUR_USERNAME/sendai.git
   cd sendai
   ```

2. **Add the upstream remote**
   ```bash
   git remote add upstream https://github.com/ai-swe-scapelabs/sendai.git
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

#### Development Workflow

1. **Stay up to date**
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Make your changes**
   - Follow the existing code style
   - Write clean, readable code
   - Add comments for complex logic

3. **Test your changes**
   ```bash
   npm test                    # Run all tests
   npm run test:coverage      # Check test coverage
   npm run lint               # Run linting
   ```

4. **Commit your changes**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

   Use conventional commit messages:
   - `feat:` for new features
   - `fix:` for bug fixes
   - `docs:` for documentation changes
   - `style:` for code style changes
   - `refactor:` for code refactoring
   - `test:` for adding tests
   - `chore:` for maintenance tasks

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**
   - Use a clear, descriptive title
   - Reference any related issues
   - Describe your changes
   - Include screenshots if applicable

## 📝 Code Style Guidelines

### General Principles

- **Keep it simple**: Write clear, straightforward code
- **Be consistent**: Follow existing patterns and conventions
- **Document**: Add comments for complex logic
- **Test**: Write tests for new functionality

### Specific Guidelines

#### JavaScript/TypeScript

- Use camelCase for variables and functions
- Use PascalCase for classes and components
- Use UPPER_SNAKE_CASE for constants
- Add JSDoc comments for functions

#### Python

- Follow PEP 8 style guide
- Use snake_case for variables and functions
- Use PascalCase for classes
- Add docstrings for functions and classes

#### File Organization

- Keep files focused and small
- Use descriptive file names
- Group related files in directories
- Follow the existing project structure

## 🧪 Testing

### Writing Tests

- **Unit tests**: Test individual functions/components
- **Integration tests**: Test how components work together
- **End-to-end tests**: Test complete user workflows

### Test Guidelines

- Write tests before or alongside code (TDD)
- Aim for high test coverage
- Test both happy path and edge cases
- Use descriptive test names
- Mock external dependencies

### Running Tests

```bash
# Run all tests
npm test

# Run specific test files
npm test -- --grep "test name"

# Run tests in watch mode
npm run test:watch

# Generate coverage report
npm run test:coverage
```

## 📖 Documentation

### Types of Documentation

- **README**: Project overview and quick start
- **API docs**: Function and class documentation
- **User guides**: How-to documentation
- **Developer docs**: Architecture and design

### Documentation Guidelines

- Keep documentation up to date
- Use clear, simple language
- Include code examples
- Add diagrams for complex concepts
- Review documentation for accuracy

## 🔍 Code Review Process

### Reviewing Pull Requests

When reviewing PRs:

1. **Check functionality**: Does the code work as intended?
2. **Review code quality**: Is the code clean and readable?
3. **Verify tests**: Are there adequate tests?
4. **Check documentation**: Is the documentation updated?
5. **Test manually**: Does it work in practice?

### Responding to Reviews

- Address feedback promptly
- Explain your reasoning for design decisions
- Be open to suggestions
- Update your PR based on feedback

## 🚀 Release Process

### Version Management

We follow [Semantic Versioning](https://semver.org/):
- **MAJOR**: Breaking changes
- **MINOR**: New features (backward compatible)
- **PATCH**: Bug fixes (backward compatible)

### Release Checklist

- [ ] All tests pass
- [ ] Documentation is updated
- [ ] CHANGELOG is updated
- [ ] Version is bumped
- [ ] Release notes are written

## 🏆 Recognition

### Contributors

We recognize all contributors through:
- GitHub contributor statistics
- Release notes acknowledgments
- Project README credits
- Community spotlights

### Ways to Contribute

- Code contributions
- Bug reports and feature requests
- Documentation improvements
- Community support
- Design and UX feedback
- Translation and localization

## 📞 Getting Help

If you need help contributing:

- **GitHub Issues**: For bug reports and feature requests
- **GitHub Discussions**: For general questions and ideas
- **Email**: Contact maintainers directly
- **Discord/Slack**: Join our community (if available)

## 📄 License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for contributing to Sendai! Your contributions help make this project better for everyone. 🎉