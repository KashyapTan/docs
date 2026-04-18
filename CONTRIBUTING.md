# Contribute to the docs

This repository hosts the Mintlify documentation site for Xpdite.

## How to contribute

### Edit on GitHub

1. Open the page you want to change.
2. Click **Edit this file**.
3. Submit a pull request with a clear summary.

### Edit locally

1. Fork and clone this repository.
2. Install Mintlify: `npm i -g mint`
3. Run `mint dev` from the docs root.
4. Open `http://localhost:3000`.
5. Run `mint broken-links` before you open a pull request.

For repository-specific development guidance, see [development.mdx](development.mdx).

## Source of truth

- Product behavior should match the code in `Xpdite/source`, `Xpdite/src`, and `Xpdite/mcp_servers`.
- Existing draft docs in `Xpdite/docs` are a starting point, not a substitute for verification.
- When a page documents an API, WebSocket event, or settings flow, verify it against the implementation before merging.

## Writing guidelines

- Use active voice and second person.
- Keep sentences concise.
- Use sentence case for headings.
- Bold UI labels such as **Settings** or **Run now**.
- Use code formatting for commands, file names, paths, API routes, and message types.
- Prefer user workflows first, then explain architecture or implementation details.
- Call out internal-only or loopback-only APIs explicitly.

## Pull request expectations

- Keep scope focused.
- Update related navigation or cross-links when you add a page.
- Include screenshots for visible UI or landing-page changes.
- Mention any assumptions if the codebase is incomplete or a feature is intentionally undocumented.
