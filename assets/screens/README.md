# Screenshots

Captured 2026-09-24 on the Android emulator (Pixel 8), signed in as a seeded demo account
("Maya", `docs/seed-showcase.sql` in the app repo) in Sunnyvale, so no real neighbourhood or
tester appears. To redo one, overwrite the file and keep the name. Nothing in the markdown
needs to change.

| File | Screen | Route |
| :-- | :-- | :-- |
| `01-map-garden.png` | Map garden, half of the hero | `(tabs)/map.tsx` → `MapGarden.tsx` |
| `02-garden-wrapped.png` | Garden Wrapped | `recap.tsx` |
| `03-hybrid-bloom.png` | A bloom with its card open BEFORE the reveal: "A bloom grew", "I want to know", no name or face. The other half of the hero | map, tap a bloom |
| `04-new-drop.png` | Leave a drop | `drops/new.tsx` |
| `05-plots.png` | Plots | `plots.tsx` |
| `06-post-composer.png` | Post composer, editing 1 of 3 | `compose.tsx` + `PhotoEditor` |
| `07-decorated-patch.png` | A decorated #25 patch | map, My garden |

## Before capturing

- **Seed a populated garden** (`docs/seed-demo-account.sql` in the app repo). An empty map is
  the worst possible hero shot.
- **Keep the set coherent:** one device, one account, one season across all six.
- Portrait, native resolution, consistent status bar in every frame.
- For `03`, confirm a bloom actually exists in the seed data before going looking for one,
  and capture it from an account that has NOT tapped "I want to know". The shot is the door
  still closed.

The placeholders are 600 × 1300, which is the iPhone 1290 × 2796 aspect ratio. Real
screenshots at native size will render correctly at the widths set in the markdown, so there
is no need to resize them.
