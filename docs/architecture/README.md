# Architecture principles

- Projects are independent by default. Each can have its own implementation, tests, documentation, and build configuration when needed.
- Keep components modular and integrate projects only when there is a concrete technical reason.
- Introduce a shared library in `crates/` only when a real cross-project requirement justifies it; do not extract speculative common code.
- Keep project-specific documentation with its project; use `docs/` for repository-wide concerns and decisions.

## Adding a project

Create a directory under `projects/` and describe its purpose in a README. Add implementation, tests, and build configuration only as the project needs them; avoid coupling it to other projects by default.
