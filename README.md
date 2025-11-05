# Curriculum Structure

Content is organized by tracks → modules → lessons/projects.

```
/tracks/{track-id}/
modules/{mod-id}-{slug}/
lessons/{lesson-id}-{slug}.md
projects/{project-id}-{slug}.md
/templates/
```


## Front-matter schema (minimum)
- `id` (string, e.g., "ADV-201-L01")
- `title` (string)
- `track` (string) and `module` (string)
- `type` ("lesson" | "project" | "resource")
- `prerequisites` (string[]), `outcomes` (string[])
- `time_suggested` (number, hours)
- `resources` ({title, url, license}[])
- `knowledge_check` ({q, a[]}[]) — optional
- `attribution` (string) — translations/derivatives

All written content is **CC BY 4.0**.
