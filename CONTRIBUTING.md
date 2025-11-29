# Contributing to Nano PDF

Thank you for your interest in contributing to Nano PDF! This document provides guidelines for contributing to the project.

## Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Nano-PDF.git
   cd Nano-PDF
   ```
3. **Install dependencies**:
   ```bash
   pip install -e .
   brew install poppler tesseract  # macOS
   ```
4. **Set up your API key**:
   ```bash
   export GEMINI_API_KEY="your_key_here"
   ```

## Development Process

### Making Changes

1. **Create a new branch** for your feature or fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** following the code style guidelines below

3. **Test your changes** thoroughly:
   - Test with various PDF files
   - Test error cases
   - Verify system dependency checks work

4. **Commit your changes** with clear, descriptive commit messages:
   ```bash
   git commit -m "Add: Brief description of what you added"
   ```

### Code Style

- Follow PEP 8 style guidelines
- Use type hints where appropriate
- Add docstrings to new functions
- Keep functions focused and simple
- Comment complex logic

### Pull Request Process

1. **Update documentation** if you've added new features
2. **Ensure your code works** on your local machine
3. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
4. **Open a Pull Request** on GitHub with:
   - Clear description of changes
   - Why the change is needed
   - Any potential issues or limitations

## Types of Contributions

### Bug Reports

Found a bug? Please open an issue with:
- Clear description of the problem
- Steps to reproduce
- Expected vs. actual behavior
- Your environment (OS, Python version, etc.)
- Sample PDF if relevant (and not confidential)

### Feature Requests

Have an idea? Open an issue describing:
- The feature and why it's useful
- How it might work
- Any alternatives you've considered

### Code Contributions

We welcome:
- Bug fixes
- New features
- Performance improvements
- Documentation improvements
- Test coverage improvements

### Documentation

Help improve:
- README clarity
- Code comments
- Examples and tutorials
- Troubleshooting guides

## Areas for Contribution

Looking for ideas? Here are some areas that need work:

- **Testing**: Add unit tests and integration tests
- **Error handling**: Improve error messages and recovery
- **Performance**: Optimize PDF processing and API usage
- **Features**:
  - Batch processing improvements
  - Configuration file support
  - More output formats
  - Better progress tracking
- **Documentation**: More examples, video tutorials, blog posts
- **Platform support**: Test and improve Windows compatibility

## Code Review

All submissions require review. We use GitHub pull requests for this purpose. Reviewers will check:
- Code quality and style
- Functionality and correctness
- Documentation updates
- Potential edge cases

## Questions?

Feel free to:
- Open an issue for questions
- Start a discussion on GitHub
- Contact the maintainers

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

Thank you for helping make Nano PDF better!
