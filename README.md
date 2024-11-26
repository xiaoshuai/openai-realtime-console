# OpenAI Realtime Console

This project is forked from [openai-realtime-console](https://github.com/openai/openai-realtime-console) and has been updated to improve dependencies and project management.

## Changes in This Fork

### Dependency Management
- Migrated the `@openai/realtime-api-beta` package from a GitHub dependency to a local directory (`src/lib`). This makes customization easier and debugging more convenient.

### Build Tool
- Switched the project setup from Create React App (CRA) to Vite. Vite offers faster build times and a modern development workflow.
