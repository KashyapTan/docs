# Xpdite documentation instructions

## About this project

- This is a [Mintlify](https://mintlify.com) documentation site for **Xpdite**
- Pages are MDX files with YAML frontmatter
- Navigation, branding, tabs, and global links live in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to validate links
- The source of truth for product behavior is the app code in `Xpdite/source`, `Xpdite/src`, and `Xpdite/mcp_servers`
- Existing product drafts and engineering notes live in `Xpdite/docs`

## Terminology

- Use `Xpdite` as the product name
- Use `tab` for a chat workspace
- Use `model provider` for Ollama, Anthropic, OpenAI, Gemini, and OpenRouter
- Use `MCP server` for subprocess tool servers
- Use `inline tool` for tools executed directly inside the backend
- Use `skill`, `artifact`, `memory`, `scheduled job`, `notification`, and `Channel Bridge` consistently
- Use `mobile channel` for Telegram, Discord, and WhatsApp integrations

## Style preferences

- Use active voice and second person
- Keep sentences concise
- Use sentence case for headings
- Bold UI elements: open **Settings**, click **Run now**
- Use code formatting for file names, commands, paths, API routes, message types, and env vars
- Lead with user workflows before implementation details
- Mark internal or loopback-only APIs clearly when documenting them

## Content boundaries

- Do not present placeholder connectors or stub MCP servers as production-ready features
- Do not imply macOS or Linux support unless the code or release process clearly supports it
- Distinguish public docs from internal APIs such as `/internal/mobile/*`
- Prefer verified behavior from code over older prose when documentation conflicts
