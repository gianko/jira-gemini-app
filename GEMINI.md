# Project: My Jira Ticket Manager
This is a simple React application build with React and Vite. It allows the user to list it tickets
and move then to 2 differents list: `Yesterday` and `Today`, and also set a status of `N` and `C`, 
there is also a third list for `Blocked` tickets.

# Tech stack
- pnpm
- Vite
- React
- Typescript
- Tanstack Query
- MUI

# Code Standars
1. All React components must be functional components using hooks.
2. Prefer TypeScript interfaces for props and state definitions.
3. avoid custom CSS files unless absolutely necessary.
4. Component files should be named in PascalCase (e.g., TaskItem.tsx).
5. Directories should be named in kebab-case (eg., task-item/TaskItem.tsx).
6. Functions and variables should be camelCase.

# Project Structure
- src/components: Reusable UI components.
- src/hooks: Custom React hooks.
- src/utils: Utility functions.
- src/types: TypeScript type definitions.

# Workflow
- Run dev: `pnpm dev`
- Build: `pnpm build`
- Preview after build: `pnpm preview`
- Lint: `pnpm lint`

# AI Directives
- When generating new components, always include a basic TypeScript interface for props.
- When generating new components also create a .test.tsx for unit test file
- When writing unit tests, focus on component behavior rather than internal implementation details.
- Use Mui's MCP
- Use Jira MCP
