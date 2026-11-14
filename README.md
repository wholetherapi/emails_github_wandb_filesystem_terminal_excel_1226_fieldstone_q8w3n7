# Fieldstone Recipe Catalogue

Source content for the public Fieldstone recipe catalogue.

Every recipe is a Markdown file under `items/`. The YAML front matter drives the
site build:

- `title` - display name of the recipe
- `slug` - stable identifier used across the catalogue
- `status` - `published` (rendered on the public site) or `draft`
- `run` - experiment run reference (`entity/project:run-id`)
- `metric` - evaluation metric recorded in the run history
- `code` - optional URL of the companion implementation repository
- `results` - per-step results snapshot maintained by the curation refresh

See the curation policy for the quarterly update rules.
