# Project Guidelines for Claude Code

This file contains guidelines and context for Claude Code when working on this project.

## Project Overview
This is a new HP (Homepage) project.

## Coding Standards
- Use modern JavaScript/TypeScript
- Follow ESLint rules if configured
- Prefer functional components for React
- Use semantic HTML5 elements
- Follow accessibility best practices (WCAG 2.1 AA)

## Directory Structure
- `/src` - Source code
- `/public` - Static assets
- `/components` - Reusable components
- `/pages` - Page components
- `/styles` - CSS/SCSS files

## Dependencies
- Prefer using existing dependencies before adding new ones
- Check package.json before installing new packages

## Git Conventions
- Use conventional commits: feat:, fix:, docs:, style:, refactor:, test:, chore:
- Keep commits atomic and focused
- Write clear commit messages

## Testing
- Write tests for new features
- Ensure existing tests pass before committing

## Security
- Never commit API keys or secrets
- Use environment variables for sensitive data
- Validate all user inputs
- Follow OWASP security guidelines