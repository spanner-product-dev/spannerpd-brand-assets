# Spanner Logo — 2024 Azure Refresh

These files are color-corrected versions of the wordmark using the **current 2024 Azure `#06A6ED`**.

## Why this folder exists

The original `Spanner-Logo-Blue-Rev-01.png`, `Spanner_Logo_Blue.svg`, and `Spanner_Logo_Blue.eps` files in the parent folder were produced in 2015 and use a legacy "Spanner Blue" of `#49B5CF` — a slightly more cyan/teal blue that doesn't match the current 2024 brand palette.

Both blues are recognizably "Spanner blue" at a glance, but they're visibly different when placed side by side or next to current-Azure accents (pipes, headers, highlights). This folder gives you a current-Azure version for any deliverable where the rest of the surface uses 2024 brand color.

## Files

| File | Format | Notes |
|---|---|---|
| `Spanner_Logo_Azure_2024.svg` | SVG, vector | Authoritative source for current-Azure use; embed inline in HTML or scale to any size |
| `Spanner_Logo_Azure_2024_320px.png` | PNG, transparent | Email signatures, small web placements |
| `Spanner_Logo_Azure_2024_640px.png` | PNG, transparent | Standard web/slide placements |
| `Spanner_Logo_Azure_2024_1280px.png` | PNG, transparent | Hero placements, large slides, 2x retina |

## When to use these vs. the originals

- **Use these (2024 Azure)** when the deliverable also uses current Azure as an accent color — decks, web pages, emails, dashboards, anything styled per `branding.md`
- **Use the originals (legacy `#49B5CF`)** when matching pre-2024 collateral that still circulates externally, or when a designer requests the historical files for archival reasons

## Still missing

- **EPS in current Azure** — would need to be re-exported by a designer from the .ai source in `1_Native Logo Files/`. Until that's done, use the SVG for vector workflows
- **Refreshed Square / Rectangle / White-on-Blue panel composites** — these legacy framed variants haven't been regenerated yet
- **Updated `1_Native Logo Files/` .ai sources** — designer task

## Generation notes

The SVG was produced by replacing every `#49B5CF` fill in `2_Export Logo Files/Spanner_Logo_Blue.svg` with `#06A6ED`. Path geometry is identical to the original — no shapes were modified, only color. PNG renders were generated from the new SVG via cairosvg at the widths above with transparent background.
