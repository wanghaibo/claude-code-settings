# Claude Code Settings and Commands for Vibe Coding

A curated collection of Claude Code configurations and custom commands designed for enhanced development workflows. This setup includes specialized commands for feature development (Kiro workflow), code analysis, GitHub integration, and knowledge management.

## Setup

```sh
# Backup original claude settings
mv ~/.claude ~/.claude.bak

# Clone the claude-code-settings
git clone https://github.com/feiskyer/claude-code-settings.git ~/.claude

```


## Commands

### Development Workflow

**Kiro Workflow** - Complete feature development from spec to execution. The Kiro commands provide a structured workflow for feature development:

1. `/kiro:spec [feature]` - Create requirements and acceptance criteria
2. `/kiro:design [feature]` - Develop architecture and component design
3. `/kiro:task [feature]` - Generate implementation task lists
4. `/kiro:execute [task]` - Execute specific implementation tasks
5. `/kiro:vibe [question]` - Quick development assistance

### Analysis & Reflection

- `/think-harder [problem]` - Enhanced analytical thinking
- `/think-ultra [complex problem]` - Ultra-comprehensive analysis
- `/reflection` - Analyze and improve Claude Code instructions
- `/reflection-harder` - Comprehensive session analysis and learning
- `/eureka [breakthrough]` - Document technical breakthroughs

### GitHub Integration

- `/gh:review-pr [PR_NUMBER]` - Comprehensive PR review and comments
- `/gh:fix-issue [issue-number]` - Complete issue resolution workflow

### Documentation & Knowledge

- `/cc:create-command [name] [description]` - Create new Claude Code commands

## Guidances

- [Claude Code with Github Copilot as Model Provider](guidances/github-copilot.md)

## LICENSE

This project is released under MIT License - See [LICENSE](LICENSE) for details.
