# ◈ AI Dotfiles

> AI assistant configs — JetBrains IDEA (AI Chat, Junie), Air, Cursor & MCP

[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)](https://www.jetbrains.com/ai/)
[![JetBrains Air](https://img.shields.io/badge/JetBrains_Air-6B57FF?style=flat-square&logo=jetbrains&logoColor=white)](https://air.dev/)
[![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=00D4FF)](https://cursor.com/)
[![MCP](https://img.shields.io/badge/MCP-5A45FF?style=flat-square&logo=anthropic&logoColor=white)](https://github.com/modelcontextprotocol/kotlin-sdk)

---

## What's Inside

| Folder       | Contents                                              |
|--------------|-------------------------------------------------------|
| `jetbrains/` | AI assistant rules, Junie agent configs, Air settings |
| `cursor/`    | Commands, plans, MCP settings                         |

---

## Structure

    ai-dotfiles/
    │
    ├── jetbrains/
    │   ├── .aiassistant/
    │   │   └── rules/
    │   │       ├── grammar.md
    │   │       └── kotlin.md
    │   ├── junie/
    │   │
    │   └── air/
    │       ├── mcp.json
    │       ├── rules/
    │       └── settings.json
    │
    └── cursor/
        └── .cursor/
            ├── commands/
            │   ├── grammer.md
            │   └── kotlin.md
            ├── plans/
            │   └── update_version_catalog.plan.md
            └── mcp.json