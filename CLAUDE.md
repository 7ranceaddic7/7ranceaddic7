# CLAUDE.md

This file provides context and guidelines for AI assistants (like Claude) working on this project.

## Project Overview

**Project Name:** [Your Project Name]
**Description:** [Brief description of what this project does]
**Primary Language(s):** [e.g., Python, JavaScript, TypeScript, etc.]
**Framework(s):** [e.g., React, Django, Express, etc.]

## Project Structure

```
[project-root]/
├── src/              # Source code
├── tests/            # Test files
├── docs/             # Documentation
├── config/           # Configuration files
└── [other-dirs]/     # Other important directories
```

**Key Directories:**
- `[directory]`: [Purpose and contents]
- `[directory]`: [Purpose and contents]

**Key Files:**
- `[filename]`: [Purpose]
- `[filename]`: [Purpose]

## Development Setup

### Prerequisites
- [Tool/Runtime] version [X.X.X] or higher
- [Other dependencies]

### Installation
```bash
# Clone the repository
git clone [repository-url]

# Install dependencies
[package-manager install command]

# Setup environment
[environment setup commands]
```

### Running the Project
```bash
# Development mode
[development command]

# Production build
[build command]

# Run tests
[test command]
```

## Code Conventions

### Style Guide
- Follow [style guide name] conventions
- Use [naming convention] for variables/functions
- Maximum line length: [number] characters
- Indentation: [spaces/tabs] ([number] spaces)

### File Organization
- Group related functionality together
- Keep files under [number] lines when possible
- One component/class per file (when applicable)

### Naming Conventions
- **Files:** [convention, e.g., kebab-case, snake_case]
- **Classes:** [convention, e.g., PascalCase]
- **Functions:** [convention, e.g., camelCase]
- **Variables:** [convention, e.g., camelCase]
- **Constants:** [convention, e.g., UPPER_SNAKE_CASE]

## Testing

### Test Structure
- Unit tests in: [location]
- Integration tests in: [location]
- E2E tests in: [location]

### Running Tests
```bash
# Run all tests
[test command]

# Run specific test file
[specific test command]

# Run with coverage
[coverage command]
```

### Writing Tests
- Aim for [X]% code coverage
- Test naming: [convention]
- Mock external dependencies when appropriate

## Build & Deployment

### Building
```bash
# Build for production
[build command]

# Build output location
[output directory]
```

### Deployment
- Deployment platform: [platform name]
- Deployment command: [command]
- Environment variables: See `.env.example`

## Dependencies

### Adding Dependencies
```bash
# Add runtime dependency
[add dependency command]

# Add development dependency
[add dev dependency command]
```

### Updating Dependencies
```bash
# Update all dependencies
[update command]

# Update specific dependency
[update specific command]
```

## Common Tasks

### Creating New [Component/Module/Feature]
1. [Step 1]
2. [Step 2]
3. [Step 3]

### Debugging
- Enable debug mode: [how to enable]
- Log location: [where logs are stored]
- Debugging tools: [tools used]

### Database Operations (if applicable)
```bash
# Run migrations
[migration command]

# Seed database
[seed command]

# Reset database
[reset command]
```

## Important Notes for AI Assistants

### DO:
- Follow the established code style and conventions
- Write tests for new functionality
- Update documentation when making changes
- Use meaningful commit messages
- Check for existing similar functionality before adding new code
- Consider performance implications
- Handle errors gracefully
- Validate user input

### DON'T:
- Commit sensitive information (API keys, passwords, etc.)
- Break existing tests
- Introduce dependencies without justification
- Ignore linter warnings
- Hardcode configuration values
- Skip error handling
- Make breaking changes without discussion

### Security Considerations
- Never expose sensitive data
- Validate and sanitize all user inputs
- Use parameterized queries for database operations
- Follow OWASP best practices
- Keep dependencies up to date
- Use environment variables for secrets

### Performance Considerations
- Optimize database queries
- Minimize API calls
- Implement caching where appropriate
- Consider memory usage
- Profile before optimizing

## Git Workflow

### Branch Naming
- Feature branches: `feature/description`
- Bug fixes: `fix/description`
- Hotfixes: `hotfix/description`

### Commit Messages
Follow [Conventional Commits](https://www.conventionalcommits.org/):
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting, etc.)
- `refactor:` Code refactoring
- `test:` Adding or updating tests
- `chore:` Maintenance tasks

### Pull Requests
- Create descriptive PR titles
- Link related issues
- Provide context in PR description
- Ensure all tests pass
- Request review from appropriate team members

## API Documentation (if applicable)

### Endpoints
[Document main API endpoints or link to API documentation]

### Authentication
[Describe authentication method]

### Rate Limiting
[Describe any rate limiting]

## Troubleshooting

### Common Issues

**Issue:** [Common problem]
**Solution:** [How to fix]

**Issue:** [Common problem]
**Solution:** [How to fix]

## Resources

- [Documentation link]
- [API reference link]
- [Style guide link]
- [Contributing guidelines]
- [Code of conduct]

## Contact & Support

- **Maintainer:** [Name/Email]
- **Issues:** [Issue tracker link]
- **Discussions:** [Discussion forum/chat link]

---

**Last Updated:** [Date]
**Version:** [Project version]
