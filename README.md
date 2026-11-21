# Personal blog filled with various thoughts and reflections

## Adding content

| To add… | Do this | Shows up on |
|---|---|---|
| A post | New file `_posts/YYYY-MM-DD-title.md` with `title:` and `topic:` at the top | Reflections & Writings, About me (Now) |
| A project | Copy `_projects/_TEMPLATE.md` to `_projects/name.md` and fill it in | Projects, its own page, About me (Now) if `status: Active` |
| A post about a project | Add `project: name` to the post's top section (the project's file name without `.md`) | The project's page, plus a link on the post |
| A note | Copy `_notes/_TEMPLATE.md` to `_notes/YYYY-MM-DD-short-name.md` | Notes, its own page, About me (Now) |
| A book or article | Copy `_reading/_TEMPLATE.md` to `_reading/name.md` and fill it in | Articles & Books, its own page, About me (Now) if `status: reading` |

The About text lives in `index.md`, your email in `_config.yml` (`email:`).
The sections in the top bar, the topics, and the Reflections & Writings sidebar title (`writings_title`) are also in `_config.yml`.
