# Mintlify documentation

## Working relationship
- You can push back on ideas-this can lead to better documentation. Cite sources and explain your reasoning when you do so
- ALWAYS ask for clarification rather than making assumptions
- NEVER lie, guess, or make up information

## Project context
- Format: MDX files with YAML frontmatter
- Config: docs.json for navigation, theme, settings
- Components: Mintlify components

## Content strategy
- Document just enough for user success - not too much, not too little
- Prioritize accuracy and usability of information
- Make content evergreen when possible
- Search for existing information before adding new content. Avoid duplication unless it is done for a strategic reason
- Check existing patterns for consistency
- Start by making the smallest reasonable changes

## docs.json

- Refer to the [docs.json schema](https://mintlify.com/docs.json) when building the docs.json file and site navigation

## Frontmatter requirements for pages
- title: Clear, descriptive page title
- description: Concise summary for SEO/navigation

## Writing standards
- Second-person voice ("you")
- Prerequisites at start of procedural content
- Test all code examples before publishing
- Match style and formatting of existing pages
- Include both basic and advanced use cases
- Language tags on all code blocks
- Alt text on all images
- Relative paths for internal links

## Git workflow
- NEVER use --no-verify when committing
- Ask how to handle uncommitted changes before starting
- Create a new branch when no clear branch exists for changes
- Commit frequently throughout development
- NEVER skip or disable pre-commit hooks

## Do not
- Skip frontmatter on any MDX file
- Use absolute URLs for internal links
- Include untested code examples
- Make assumptions - always ask for clarification

## Decine Project Context

### About Decine
Decine is a streaming service application that provides users with a clean, simple interface for accessing media content. The backend infrastructure uses Jellyfin and ARR applications (Sonarr, Radarr, etc.) but this complexity is completely hidden from end users.

### Documentation Goals
- **User-focused**: Document installation, configuration, and content request workflows
- **Backend abstraction**: Never expose Jellyfin/ARR technical details to users
- **Self-service**: Enable users to understand and use the system independently
- **Simple language**: Avoid technical jargon; focus on user actions and outcomes

### Key Documentation Areas
1. **Installation Guide**: Step-by-step setup for new users
2. **Configuration**: User settings, preferences, and account setup
3. **Content Requests**: How users request movies, TV shows, and other media
4. **Usage Guide**: Daily operations, browsing, searching, watching
5. **Troubleshooting**: Common issues and user-fixable problems

### Content Strategy for Decine
- Focus on user benefits and capabilities, not technical implementation
- Use screenshots and visual guides where helpful
- Provide clear prerequisites and step-by-step instructions
- Include both basic usage and advanced user features
- Keep content evergreen - avoid version-specific details unless necessary
