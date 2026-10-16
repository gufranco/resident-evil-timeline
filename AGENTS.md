# Resident Evil: Canonical Timeline

## Project Description

A comprehensive reference documenting the canonical story of every Resident Evil game, DLC, and CG animated project in chronological (in-universe) order. The primary artifact is `README.md`.

## Structure

- `README.md`: The complete timeline in English with detailed story summaries and Mermaid diagrams
- `README.pt-br.md`: Brazilian Portuguese translation
- `README.pt-eu.md`: European Portuguese translation
- `README.it.md`: Italian translation
- `README.es.md`: Spanish translation
- `.claude/`: Project configuration, commands, and specs

## Translations

All five language versions must stay in sync. When updating content:

1. Make changes to the English `README.md` first
2. Apply the same changes to all four translations
3. Mermaid diagrams, game titles, character names, and technical terms remain in English across all versions
4. Section headers for metadata use the target language: "Resumo do Enredo" instead of "Plot Summary"
5. Use `/update-timeline` which will prompt for all five versions

## Content Conventions

- Games are ordered by in-universe chronology, not release date
- Remakes are the preferred source for story details. When original and remake details conflict, prefer the remake
- All canonical entries are included: mainline games, canon spin-offs, canon DLCs, and CG animated films/series
- Non-canon entries (Operation Raccoon City, Gaiden, RE:Verse, Resistance, Mercenaries 3D) are excluded from the timeline but listed in the canon status table
- S.D. Perry novels are NOT canon
- Live-action films and series are NOT canon
- CG animated projects (Degeneration, Damnation, Vendetta, Death Island, Infinite Darkness) ARE canon

## Section Format

Every game/film entry in the README follows this structure:

```
### Title

**In-Universe Dates:** exact dates
**Location:** where the events take place
**Protagonists:** name (role), name (role)
**Antagonists:** name (role)

#### Plot Summary

Detailed chronological plot.

#### Key Biological Threats

BOWs and viruses encountered.

#### Lore Significance

What this entry reveals about the broader Resident Evil universe.
```

## Lore Accuracy Rules

- Dates must come from in-game documents, official Capcom sources, or Resident Evil Wiki
- When sources conflict, prefer: 1) in-game documents, 2) official Capcom publications, 3) Resident Evil Wiki
- Speculative dates must be marked as "approximate" or "estimated"
- Cross-reference at least two sources for each date claim
- Never fabricate dates or plot details from memory

## Updating This Document

When a new Resident Evil game, DLC, or CG film is released:

1. Use `/update-timeline` for guided assistance
2. Research the entry's in-universe dates and full plot
3. Insert the section at the correct chronological position
4. Update both Mermaid diagrams (timeline overview and 1998 gantt if applicable)
5. Update the canon status table
6. Update the character appearances table
7. Cross-reference connections with existing entries
8. Update the viral genealogy diagram if new biological agents are introduced

Use `/verify-lore` periodically to fact-check the document against current sources.

## Trusted Sources

- Resident Evil Wiki (Fandom): primary reference for dates, plot details, and canon status
- Project Umbrella: detailed chronological analysis and translations of Japanese-exclusive materials
- Capcom Official (residentevil.com): official announcements and canon confirmations
- Wikipedia: secondary cross-reference for release information and plot summaries
