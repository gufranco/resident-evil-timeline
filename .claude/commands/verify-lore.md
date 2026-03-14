Fact-check the Resident Evil canonical timeline in README.md against current sources.

## Arguments

$ARGUMENTS

If a specific section or game title is provided, verify only that section. Otherwise, verify the entire document.

## Process

1. **Read the full README.md.**

2. **For each game/film entry**, verify the following against the Resident Evil Wiki (Fandom) and at least one additional source:
   - In-universe dates are correct
   - Character names and roles are accurate
   - Major plot points are not missing or incorrect
   - Biological threat names and descriptions are accurate
   - Lore connections are valid

3. **Check for newly released content** that should be added:
   - Search for "Resident Evil new game 2025 2026" and similar queries
   - Check if any new DLCs, CG films, or remakes have been announced or released
   - If new content exists, flag it and suggest using `/update-timeline` to add it

4. **Verify the Mermaid diagrams:**
   - Timeline entries match the game sections
   - Gantt chart dates align with the text
   - Viral genealogy relationships are accurate

5. **Check the canon status table** against the Resident Evil Wiki's current canon policy.

6. **Report findings** in a structured format:

```
## Verification Report

### Confirmed Accurate
- [list of verified sections]

### Corrections Needed
- [section]: [what's wrong] → [what it should be] (source: [url])

### Missing Content
- [new entries that should be added]

### Diagrams
- [any diagram issues]
```

## Rules

- Do not modify the README directly. Present findings and let the user decide what to update.
- Flag uncertainty. If sources disagree, present both versions.
- Check dates first, as they are the most common source of errors.
- Verify character death/survival status, as fan wikis sometimes contain spoilers that get edited.
