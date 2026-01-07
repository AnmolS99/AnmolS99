# CLAUDE.md - AI Assistant Guide for AnmolS99 Profile Repository

## Repository Overview

This is a **GitHub Profile README Repository** - a special repository type where the repository name matches the GitHub username (`AnmolS99/AnmolS99`). The README.md file in this repository automatically appears on the owner's GitHub profile page at https://github.com/AnmolS99.

**Owner:** Anmol Singh (Anmol_singh@live.no)
**Purpose:** Personal GitHub profile biography and showcase
**Type:** Static documentation repository
**Primary File:** README.md (the only tracked file)

## Codebase Structure

```
/home/user/AnmolS99/
├── README.md              # Main profile content (displays on GitHub profile)
├── CLAUDE.md              # This file - AI assistant documentation
└── .git/                  # Git repository metadata
```

### Key Characteristics

- **Minimal Structure:** Only contains README.md for profile display
- **No Dependencies:** No package.json, requirements.txt, or build tools
- **No CI/CD:** No automated testing or deployment pipelines
- **Static Content:** Pure Markdown documentation, no code execution
- **Single Author:** Maintained solely by Anmol Singh

## Content Guidelines

### What the Profile README Should Include

The profile README serves as Anmol's professional introduction on GitHub. It should contain:

1. **Personal Introduction**
   - Current role and company
   - Professional interests and specializations
   - Educational background

2. **Projects and Work**
   - Notable projects (e.g., chess bot on Lichess)
   - Links to live projects or demos
   - Technical achievements

3. **Content and Writing**
   - Blog posts and technical writing
   - Recent articles with links
   - Areas of expertise

4. **Professional Presence**
   - Links to external platforms (blog, LinkedIn, etc.)
   - Contact information (if desired)

### What to Avoid

- **Excessive Emojis:** Use sparingly and only where they add value
- **Outdated Information:** Always verify dates, positions, and project status
- **Broken Links:** Validate all external links before committing
- **Generic Content:** Avoid boilerplate text; keep it personal and authentic
- **Overly Long:** Profile READMEs should be scannable; aim for concise content
- **Code Blocks:** This isn't a code showcase; link to actual repositories instead

## Git Workflow

### Branch Strategy

- **Main Branch:** `main` (currently not checked out)
- **Feature Branches:** Use descriptive names prefixed with `claude/` for AI-assisted work
- **Current Branch:** `claude/add-claude-documentation-rvQbv`

### Making Changes

1. **Read First:** Always read README.md before making changes
2. **Preserve Tone:** Maintain Anmol's professional yet approachable voice
3. **Validate Links:** Test all external links for accessibility
4. **Check Formatting:** Ensure Markdown renders correctly on GitHub
5. **Commit Messages:** Use clear, descriptive messages like "Update README.md"

### Committing and Pushing

```bash
# Stage changes
git add README.md CLAUDE.md

# Commit with descriptive message
git commit -m "Update profile with latest blog post"

# Push to current branch
git push -u origin claude/add-claude-documentation-rvQbv
```

**Important:** Always use `git push -u origin <branch-name>` for feature branches starting with `claude/`.

## Development Workflows

### Updating the Profile README

1. **Read Current Content**
   - Use Read tool to view `/home/user/AnmolS99/README.md`
   - Understand the current structure and tone

2. **Identify Changes Needed**
   - New job position or company
   - Recent blog posts or projects
   - Updated links or achievements
   - Improved formatting or organization

3. **Make Targeted Edits**
   - Use Edit tool for precise changes
   - Preserve existing structure unless explicitly asked to restructure
   - Maintain consistent emoji usage
   - Keep line lengths reasonable for readability

4. **Verify Markdown Syntax**
   - Check that links are formatted correctly: `[text](url)`
   - Ensure headers use proper levels (# for h1, ## for h2, etc.)
   - Validate that lists are properly formatted

5. **Commit Changes**
   - Use descriptive commit messages
   - Follow the pattern seen in git history: "Update README.md"
   - Push to the appropriate branch

### Profile Maintenance Best Practices

- **Keep It Current:** Update when job, projects, or blog posts change
- **Link Validation:** Periodically check that external links still work
- **Relevance:** Remove outdated projects or information
- **Consistency:** Maintain consistent formatting and style
- **Brevity:** GitHub profiles should be scannable in 30 seconds

## AI Assistant Guidelines

### When Working on This Repository

1. **Understand the Context**
   - This is a personal profile, not a code project
   - Changes should reflect Anmol's actual achievements and work
   - Don't invent or fabricate information

2. **Tone and Voice**
   - Professional but approachable
   - Technically focused (AI, software engineering)
   - Authentic and personal, not corporate

3. **Content Updates**
   - Only add information that can be verified or is provided by the user
   - Maintain the existing structure unless asked to redesign
   - Keep the focus on professional accomplishments

4. **Markdown Best Practices**
   - Use GitHub-flavored Markdown
   - Test links before committing
   - Use emoji sparingly (current profile uses minimal emoji)
   - Ensure proper formatting for lists, headers, and links

5. **Git Operations**
   - Always read files before editing
   - Use descriptive commit messages
   - Push to feature branches for review
   - Follow the branch naming convention: `claude/description-xxxxx`

### Common Tasks

**Task: Add a New Blog Post**
```markdown
1. Read README.md to see current blog section format
2. Edit the blog section to add the new post
3. Maintain the same formatting pattern
4. Include title and link in format: [Title](URL)
5. Commit with message: "Update README.md with latest blog post"
```

**Task: Update Current Role**
```markdown
1. Read README.md to locate the role description
2. Edit the specific line with new company/position
3. Preserve emoji and formatting
4. Commit with message: "Update README.md with new position at [Company]"
```

**Task: Add a New Project**
```markdown
1. Read README.md to understand project listing format
2. Add new bullet point following existing pattern
3. Include project name, description, and link
4. Commit with message: "Update README.md with [Project Name]"
```

### Things to Avoid

- **Over-engineering:** This is a simple profile; don't add complexity
- **Creating New Files:** Unless explicitly requested, only modify README.md
- **Adding Build Tools:** No need for linters, formatters, or CI/CD
- **Markdown Extensions:** Stick to standard GitHub-flavored Markdown
- **Excessive Changes:** Make targeted updates, not complete rewrites

## Current State Analysis

**Git Status:** Clean working tree
**Branch:** `claude/add-claude-documentation-rvQbv`
**Last Commit:** cbabf11 - "Update README.md" (Jan 5, 2026)
**Commit History:** 11 commits spanning 3+ years
**Pattern:** Periodic updates every few months

**Recent Commit History:**
- cbabf11 - Update README.md (Jan 5, 2026)
- 8f544e8 - Update README.md (Jan 5, 2026)
- 16ff482 - Update README.md (Sep 30, 2025)
- fb6f135 - Update README.md (Feb 9, 2025)
- 325064f - Update README.md (Feb 9, 2025)

**Observation:** All commits follow the same simple pattern: "Update README.md". This simplicity should be maintained.

## File Paths Reference

All file operations use absolute paths:

- **Profile README:** `/home/user/AnmolS99/README.md`
- **AI Documentation:** `/home/user/AnmolS99/CLAUDE.md`
- **Git Config:** `/home/user/AnmolS99/.git/config`

## Troubleshooting

### Common Issues and Solutions

**Issue:** Push fails with 403 error
**Solution:** Ensure branch name starts with `claude/` and ends with the session ID

**Issue:** Markdown not rendering correctly
**Solution:** Validate syntax at https://github.github.com/gfm/ or use a Markdown preview tool

**Issue:** Links not working
**Solution:** Check URL format `[Text](https://example.com)` and test URLs in browser

**Issue:** Profile not updating on GitHub
**Solution:** Changes must be pushed to the `main` branch to appear on profile; feature branches are for development

## Resources

- **GitHub Profile README Guide:** https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme
- **Markdown Guide:** https://www.markdownguide.org/basic-syntax/
- **GitHub Flavored Markdown:** https://github.github.com/gfm/
- **Emoji Cheat Sheet:** https://github.com/ikatyang/emoji-cheat-sheet

## Quick Reference

### Essential Commands

```bash
# View current git status
git status

# Read the profile README
cat README.md

# Check git history
git log --oneline -10

# View current branch
git branch --show-current

# Push to feature branch
git push -u origin claude/add-claude-documentation-rvQbv
```

### Profile README Template Structure

```markdown
### Hi there 👋

[Brief introduction with current role and interests]

- 🎓 [Educational background]
- ♟ [Projects and work]
- ✍️ [Writing and content]

[Additional sections as needed]
```

## Changelog

**2026-01-07:** Created CLAUDE.md with comprehensive AI assistant documentation

---

**Note for AI Assistants:** This repository is intentionally simple. Resist the urge to add complexity, build tools, or additional files unless explicitly requested. The goal is to maintain a clean, professional GitHub profile README that accurately represents Anmol Singh's work and interests.
