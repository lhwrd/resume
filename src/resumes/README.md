# Resume Variant Sources

Store job-description-specific resume YAML files in this folder.

## Naming convention

- Use lowercase kebab-case slugs and the required suffix: `<job-slug>_CV.yaml`.
- Example: `security-data-engineer_CV.yaml`.

## Workflow behavior

- Main source file: `src/Lucas_Howard_CV.yaml`
  - Renders markdown to project `README.md`.
- Variant source files: `src/resumes/*_CV.yaml`
  - Render markdown to `docs/resumes/<filename>.md`.
  - Render PDFs to `rendercv_output/<filename>.pdf`.
