# SKILL.md

## Workspace Overview

This workspace is focused on building modern web applications using:

* React
* TypeScript
* TailwindCSS
* Node.js
* REST APIs

The goal is to maintain clean architecture, reusable components, and secure development practices.

---

## Coding Standards

### Frontend

* Use functional React components
* Prefer TypeScript over JavaScript
* Use TailwindCSS for styling
* Keep components modular and reusable
* Avoid inline styles unless necessary

### Backend

* Validate all user input
* Never trust client-side authorization
* Use async/await instead of callbacks
* Keep API responses consistent

---

## Security Rules

* Enforce server-side authorization checks
* Never expose sensitive IDs unnecessarily
* Validate permissions on every request
* Sanitize user-generated content
* Avoid storing secrets in frontend code

---

## Git Workflow

* Create feature branches:
  feature/<name>

* Fix branches:
  fix/<name>

* Use clear commit messages:

  * feat:
  * fix:
  * refactor:
  * docs:

Example:
feat: add workspace invitation system

---

## Folder Structure

src/
├── components/
├── pages/
├── hooks/
├── services/
├── utils/
├── types/

---

## API Rules

* Use REST naming conventions
* Return proper HTTP status codes
* Handle errors consistently
* Implement rate limiting where needed

---

## Performance

* Lazy load heavy components
* Optimize images/assets
* Avoid unnecessary re-renders
* Cache API requests when possible

---

## Testing

* Test authorization logic carefully
* Validate edge cases
* Test role-based permissions
* Verify private/public access transitions

---

## Notes

* Security and authorization issues are high priority
* All permission changes must invalidate previous access states
* Keep the codebase readable and documented
