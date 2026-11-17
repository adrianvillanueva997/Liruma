# Repository conventions

- Keep projects independent by default; integrate them only for a concrete technical need.
- Add shared Rust libraries to `crates/` only when actual cross-project requirements justify them.
- Keep project-specific documentation in its project and repository-wide documentation in `docs/`.
- Use `experiments/` for prototypes and research, and add infrastructure or repository tools only when needed.
- Preserve existing work and avoid introducing speculative implementations, dependencies, or configuration.
