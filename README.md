# Personal blog filled with various thoughts and reflections

## Adding content

| To add… | Do this | Shows up on |
|---|---|---|
| A post | New file `_posts/YYYY-MM-DD-title.md` with `title:` and `topic:` at the top | Reflections & Writings, About (Now) |
| A project | Copy `_projects/_TEMPLATE.md` to `_projects/name.md` and fill it in | Projects, its own page, About (Now) if `status: Active` |
| A post about a project | Add `project: name` to the post's top section (the project's file name without `.md`) | The project's page, plus a link on the post |
| A note | Copy `_notes/_TEMPLATE.md` to `_notes/YYYY-MM-DD-short-name.md` | Notes, About (Now) |
| A book or article | Add an entry at the top of the list in `_data/reading.yml` (examples are in the file) | Articles & Books, About (Now) if `status: reading` |

The About text lives in `index.md`, your email in `_config.yml` (`email:`).
The sections in the top bar and the topics in the Reflections & Writings sidebar are also listed in `_config.yml`.
