# BigAshFireplace-NY — Patterns (GitHub prep)

**Client ID:** `BigAshFireplace-NY`  
**Status:** Ready for review (not yet pushed to GitHub)

## Folder structure

```
BigAshFireplace-NY/
└── Patterns/
    ├── Header.html
    ├── HeroSection.html
    ├── QuickActionsSection.html
    └── Forms/
        └── (empty — ready for form patterns)
```

## Patterns included (3)

| File | Pattern | Cloudflare images |
|------|---------|-------------------|
| `Patterns/Header.html` | Header (top bar + nav) | Logo: `images.adept.plus/BigAshFireplace-NY/big-ash-logo` (flexible variant) |
| `Patterns/HeroSection.html` | Hero | Background: `images.adept.plus/BigAshFireplace-NY/hero-dog-fireplace` |
| `Patterns/QuickActionsSection.html` | Quick Actions | None (text-only) |

## Cloudflare asset manifest

All raster images use absolute `https://images.adept.plus/...` URLs — no local paths. Safe for GitHub hosting.

| Asset | URL |
|-------|-----|
| Logo | `https://images.adept.plus/BigAshFireplace-NY/big-ash-logo/w=141,fit=scale-down` |
| Hero background | `https://images.adept.plus/BigAshFireplace-NY/hero-dog-fireplace/background` |

## Notes

- **Footer:** Not included — no Footer section was built from Figma in this pass. Add `Footer.html` before launch if required.
- **Forms:** `Patterns/Forms/` is empty and ready for form HTML when available.
