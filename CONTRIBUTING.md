# Contributing to Awesome Physical Engineering AI

Thanks for helping engineers find useful AI tools.

## Scope

Include systems that create, modify, interpret, validate, or operate physical-engineering artifacts. CAD, CAE, CAM, inspection, maintenance, materials, robotics, and electronics are in scope.

Describe the AI mechanism and the engineering output. Numerical solvers, CAD kernels, generic agent frameworks, and deterministic automation belong in **Engineering Foundations** unless the entry describes a concrete AI-assisted integration.

## Adding or updating an entry

1. Check the README and **Removed / Reclassified** history for duplicates.
2. Use the existing category and preserve its grouping. Add one primary entry; use cross-references when a tool spans categories.
3. Match the table in that section. For the main tool tables, use:

   ```markdown
   | [Name](https://official-project.example/) | Engineering task | AI mechanism | Output / action | ✅ | **Active** |
   ```

   Connector tables use `Project | Target | What it does | Availability | Maturity`. Research and benchmark tables have their own headings.
4. Keep each cell concise. Describe supported capabilities, formats, and access limits without marketing superlatives.
5. In the PR description, provide the primary sources and the date you checked them. Prefer official documentation, release notes, model cards, licenses, and the authors' papers or repositories.
6. Disclose if you maintain the project or represent its vendor.

## Availability and maturity

Use the [README definitions](readme.md#availability--maturity).

- **Production** requires documented released access. A demo, press announcement, waitlist, or planned release date is insufficient.
- **Preview** covers beta and limited customer rollouts.
- **Active** describes maintained, usable open projects. Recent commits alone do not establish engineering reliability.
- **Experimental** describes early integrations and alpha projects.
- **Research** identifies research implementations and models.
- **Announced** is appropriate when release is planned but current access is not established.

Check code, model weights, and datasets separately. Use ✅ only with a declared open-source license, 🟡 for source-available or mixed terms, 🔒 for proprietary products, and ⚪ when public code has no verified reuse license. GitHub's automatic license detection is a starting point; inspect the actual files when it is inconclusive.

## Quality checks

- Open the exact destination links, including replacements after a repository rename.
- Distinguish a confirmed missing page from rate limiting, bot protection, and a temporary timeout.
- Check the engineering task, AI mechanism, output formats, and maturity against the sources.
- Review maintenance when a project has had no activity for over 12 months. Keep historically useful research baselines clearly labeled; move inactive early experiments to the curation history.
- Preserve stable section anchors and check relative links with the exact filename case.
- For a broad audit, add a dated note under `docs/audits/` recording consequential changes, evidence, and unresolved checks. Update the audit badge only after that review.

## New categories

Open an issue explaining the engineering workflow and representative resources before proposing a new category.

## Code of conduct

Be respectful and make evidence-based suggestions. This is a community resource for engineers building physical products.
