workspace_overview:
  description: "This workspace is focused on building modern web applications"
  technologies:
    - React
    - TypeScript
    - TailwindCSS
    - Node.js
    - REST APIs
  goals:
    - "Maintain clean architecture"
    - "Reusable components"
    - "Secure development practices"

coding_standards:
  frontend:
    - "Use functional React components"
    - "Prefer TypeScript over JavaScript"
    - "Use TailwindCSS for styling"
    - "Keep components modular and reusable"
    - "Avoid inline styles unless necessary"
  backend:
    - "Validate all user input"
    - "Never trust client-side authorization"
    - "Use async/await instead of callbacks"
    - "Keep API responses consistent"

security_rules:
  - "Enforce server-side authorization checks"
  - "Never expose sensitive IDs unnecessarily"
  - "Validate permissions on every request"
  - "Sanitize user-generated content"
  - "Avoid storing secrets in frontend code"

git_workflow:
  branch_naming:
    feature: "feature/<name>"
    fix: "fix/<name>"
  commit_messages:
    - "feat:"
    - "fix:"
    - "refactor:"
    - "docs:"
  example: "feat: add workspace invitation system"

folder_structure:
  src:
    - components
    - pages
    - hooks
    - services
    - utils
    - types

api_rules:
  - "Use REST naming conventions"
  - "Return proper HTTP status codes"
  - "Handle errors consistently"
  - "Implement rate limiting where needed"

performance:
  - "Lazy load heavy components"
  - "Optimize images/assets"
  - "Avoid unnecessary re-renders"
  - "Cache API requests when possible"

testing:
  - "Test authorization logic carefully"
  - "Validate edge cases"
  - "Test role-based permissions"
  - "Verify private/public access transitions"

notes:
  - "Security and authorization issues are high priority"
  - "All permission changes must invalidate previous access states"
  - "Keep the codebase readable and documented"
