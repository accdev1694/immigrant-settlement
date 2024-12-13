
# Contributing to Immigrant Settlement

We love your input! We want to make contributing to Immigrant Settlement as easy and transparent as possible, whether it's:
- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## Development Process
We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.

## Pull Request Process
1. Fork the repo and create your branch from `develop`
2. If you've added code that should be tested, add tests
3. If you've changed APIs, update the documentation
4. Ensure the test suite passes
5. Make sure your code lints
6. Issue that pull request!

## Code Style Guide
1. Use ESLint and Prettier configurations provided in the project
2. Follow existing naming conventions:
   - Variables/functions: camelCase
   - Classes: PascalCase
   - Constants: UPPERCASE_WITH_UNDERSCORES
   - Files: kebab-case
   
## Commit Message Guidelines
We follow the Conventional Commits specification:
- feat: A new feature
- fix: A bug fix
- docs: Documentation changes
- style: Code style changes (formatting, etc)
- refactor: Code changes that neither fix bugs nor add features
- perf: Performance improvements
- test: Adding or modifying tests
- chore: Maintenance tasks

Example:

feat: add email verification system
fix: resolve database connection timeout
docs: update API documentation

## Testing Requirements
- Write unit tests for new features
- Maintain or improve test coverage
- Run all tests before submitting PR

## Issue Reporting Guidelines
When creating an issue, please:
1. Check existing issues to avoid duplicates
2. Use provided issue templates
3. Include detailed steps to reproduce bugs
4. Include relevant logs/screenshots

## Development Setup
1. Prerequisites
   - Node.js (v18 or higher)
   - MongoDB
   - Git

2. Environment Setup
   ```bash
   # Clone the repository
   git clone <your-fork-url>
   cd immigrant-settlement

   # Install dependencies
   npm install

   # Set up environment variables
   cp .env.example .env

   # Start development server
   npm run dev 
   ```

   Code Review Process

Another developer will review your code
Address any comments/feedback
Once approved, maintainers will merge
Clean up your branch after merge

Community

Be respectful and inclusive
Help others in the community
Share knowledge and experiences
Follow our Code of Conduct

Code of Conduct
Our Pledge
We pledge to make participation in our project and our community a harassment-free experience for everyone.
Our Standards
Examples of behavior that contributes to creating a positive environment:

Using welcoming and inclusive language
Being respectful of differing viewpoints and experiences
Gracefully accepting constructive criticism
Focusing on what is best for the community
Showing empathy towards other community members

Our Responsibilities
Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.
Questions?

Create a GitHub Issue
Contact the maintainers
Join our development community

License
By contributing, you agree that your contributions will be licensed under the MIT License.