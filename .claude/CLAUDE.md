# Design Resources Library

## Project Overview
A comprehensive, curated collection of design resources for developers and designers. Backed up to private GitHub repository with multiple export formats.

## Quick Start for AI Sessions
1. **ALWAYS read PROGRESS.md first** - Contains current state and resume point
2. Work through categories sequentially (see PROGRESS.md for next category)
3. Verify each URL before adding
4. Update PROGRESS.md after completing each category
5. Commit and push frequently

## Repository Structure
```
design-resources/
├── README.md          # Main catalog (35 categories)
├── PROGRESS.md        # Session tracking - READ THIS FIRST
├── .claude/CLAUDE.md  # This file
├── assets/            # Images, header
├── exports/
│   ├── resources.json          # Full JSON export
│   └── by-category/*.json      # Per-category JSON
└── obsidian/          # Vault-compatible markdown files
```

## Categories (35 Total)

### Graphics & Assets (1-8)
1. UI Graphics
2. Fonts
3. Colors
4. Icons
5. Logos
6. Favicons
7. Icon Fonts
8. Stock Photos

### Media Resources (9-11)
9. Stock Videos
10. Stock Music & Sound Effects
11. Vectors & Clip Art

### UI/Product (12-13)
12. Product & Image Mockups
13. UI Components & Kits

### Web Development (14-18)
14. HTML & CSS Templates
15. CSS Frameworks
16. CSS Methodologies
17. CSS Animations
18. Javascript Animation Libraries

### Data Visualization (19)
19. Javascript Chart Libraries

### Framework-Specific UI (20-24)
20. React UI Libraries
21. Vue UI Libraries
22. Angular UI Libraries
23. Svelte UI Libraries
24. React Native UI Libraries

### Professional Tools (25-30)
25. Design Systems & Style Guides
26. Online Design Tools
27. Downloadable Design Software
28. Design Inspiration
29. Image Compression
30. Chrome Extensions

### Additional (31-35)
31. Firefox Extensions
32. AI Graphic Design Tools
33. AI/ML Development Tools
34. No-Code/Low-Code Platforms
35. Others

## Resource Entry Format
```markdown
| Website | Description |
|---------|-------------|
| [Name](URL) | Brief description |
```

## Workflow Per Category
1. Extract resources from source
2. Verify URL is active (HTTP 200)
3. Write original description
4. Add to README.md section
5. Update exports/resources.json
6. Update obsidian/{category}.md
7. Update PROGRESS.md
8. Commit changes
9. Push to GitHub

## Primary Source
- bradtraversy/design-resources-for-developers (~1,100 resources)

## Context Window Management
- PROGRESS.md is the source of truth for session state
- Work in batches of 1-2 categories per session
- Always update PROGRESS.md before session ends
- If context runs low, commit current progress and note position

## Commands
- Resume: Read PROGRESS.md, continue from "Next Category"
- Export: Generate JSON from README.md tables
- Verify: Check all URLs in a category

## GitHub
- Repository: brrhlv/design-resources (private)
- Remote: origin
