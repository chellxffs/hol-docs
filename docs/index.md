# House of Light Wiki

Welcome to the **House of Light** wiki — a reference for characters, lore, locations, and the world of the series.

Use the navigation above to explore, or search for any entry.

---

## Quick Navigation

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; margin-top: 1rem;">

<div style="border: 1px solid #8b6914; padding: 1rem; background: #0c1a0e;">
<strong><a href="characters/">Characters</a></strong><br>
Protagonists, allies, and antagonists of the series.
</div>

<div style="border: 1px solid #8b6914; padding: 1rem; background: #0c1a0e;">
<strong><a href="world/">World</a></strong><br>
Overview of the world, its peoples, and its history.
</div>

<div style="border: 1px solid #8b6914; padding: 1rem; background: #0c1a0e;">
<strong><a href="locations/">Locations</a></strong><br>
Realms, cities, and places of significance.
</div>

<div style="border: 1px solid #8b6914; padding: 1rem; background: #0c1a0e;">
<strong><a href="lore/">Lore & Magic</a></strong><br>
Magic systems, religions, factions, and history.
</div>

<div style="border: 1px solid #8b6914; padding: 1rem; background: #0c1a0e;">
<strong><a href="timeline/">Timeline</a></strong><br>
Chronological events of the series.
</div>

</div>

---

## Adding a New Page

1. Create a `.md` file in the appropriate folder (e.g. `docs/characters/my-character.md`).
2. Add frontmatter tags at the top:
   ```yaml
   ---
   tags:
     - Characters
     - Female
   ---
   ```
3. Copy the structure from [the example character page](characters/example-character.md) for character pages.
4. Run `mkdocs serve` locally to preview, then commit and push to publish.
