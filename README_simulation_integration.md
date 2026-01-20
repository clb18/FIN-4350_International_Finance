# International Finance Simulation (Quarto section)

## Files included
- `index.qmd` (landing page)
- `timeline.qmd`
- `countries.qmd`
- `roles.qmd`
- `decisions.qmd`
- `weekly-briefs.qmd` (release script/templates by week)
- `shock.qmd`
- `markets.qmd`
- `deliverables.qmd`
- `grading.qmd`
- `faq.qmd`

## Add to your existing sidebar/TOC
In `_quarto.yml`, add a new section under your existing navigation. Example:

```yaml
website:
  sidebar:
    contents:
      - section: "Simulation"
        contents:
          - simulation/index.qmd
          - simulation/timeline.qmd
          - simulation/countries.qmd
          - simulation/roles.qmd
          - simulation/decisions.qmd
          - simulation/weekly-briefs.qmd
          - simulation/shock.qmd
          - simulation/markets.qmd
          - simulation/deliverables.qmd
          - simulation/grading.qmd
          - simulation/faq.qmd
```

If you use `book:` or a different navigation block, keep the same paths but place them in your site’s existing structure.

## Notes
- All pages are written to be student-facing.
- Instructor-only guidance is placed in clearly labeled callout blocks so you can remove or keep them.
- Canvas submissions: the deliverables page references Canvas rather than on-site uploads.
