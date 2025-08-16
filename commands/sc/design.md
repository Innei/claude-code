---
allowed-tools: [Read, Grep, Glob, Edit, TodoWrite]
description: "Design system architecture, APIs, and component interfaces"
---

# /sc:design - System and Component Design

## Purpose
Design system architecture, APIs, component interfaces, and technical specifications.

## Usage
```
/sc:design [--type architecture|api|component|database]
```

## Arguments
- `--type` - Design type (architecture, api, component, database), if not provided, you should auto detect the type
- `--iterative` - Enable iterative design refinement, default is true

## Execution
1. Analyze requirements and design constraints
2. Create initial design concepts and alternatives
3. Develop detailed design specifications
4. Validate design against requirements and best practices
5. Generate design documentation and implementation guides

## Claude Code Integration
- Uses Read for requirement analysis
- Applies TodoWrite for design task tracking
- Maintains consistency with architectural patterns