# Digital Petrology Catalog

A collaborative digital field notebook and catalog of rock samples for geological research, education, and environmental history.

## Purpose
This repository serves as a structured, searchable, and version-controlled database of rock samples from various locations worldwide. Each entry documents physical characteristics, geological context, and environmental significance, enabling preliminary research and educational use.

## Data Structure
All rock sample entries are stored as Markdown files in the `data/` directory, following a consistent template (`data/rock_template.md`). Each file includes:
- **Frontmatter** with metadata (sample ID, rock type, location, collector, date).
- **Physical Description** (color, texture, grain size, hardness, notable features).
- **Geological Context** (formation name, geologic era/period, environment of deposition/formation).
- **Environmental Significance** (interpretation of past climate, environment, or geological events).

## Contribution Process
To add a new rock sample to the catalog:

1. **Claim a Sample** – Create an issue titled "New Entry: [Rock Name] – [Location]" and assign it to yourself.
2. **Create a Branch** – From `main`, create a branch named `add-[rock-name]-[location]`.
3. **Document the Sample** – In the `data/` directory, create a new Markdown file using the sample ID as the filename (e.g., `SAMPLE001.md`). Fill out every section of the template with detailed, accurate information.
4. **Submit for Review** – Open a pull request that links to the issue (e.g., "Closes #1") and request a review from a collaborator.
5. **Address Feedback** – Respond to review comments by pushing additional commits to your branch.
6. **Merge** – Once approved, merge the pull request using **squash and merge** to keep the history clean.

The linked issue will automatically close after the pull request is merged.

## Getting Started
- Browse existing samples in the `data/` folder.
- Use the template (`data/rock_template.md`) as a guide for new entries.
- Ensure each sample has a unique `sample_id` and that all required fields are completed.

## License
This catalog is open‑source and available under the [MIT License](LICENSE). Contributors retain no proprietary rights over the data; the goal is to build a shared, freely usable resource for the geological community.