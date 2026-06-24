# Resume Variants

This folder stores markdown outputs for job-description-specific resume variants.

## Source convention

- Variant YAML sources live in `src/resumes/`.
- Filenames must follow `<job-slug>_CV.yaml` (example: `security-data-engineer_CV.yaml`).

## Render behavior

- `src/Lucas_Howard_CV.yaml` is the main resume and is the only source that updates the project `README.md`.
- Every variant in `src/resumes/*_CV.yaml` renders to a matching markdown file here.
