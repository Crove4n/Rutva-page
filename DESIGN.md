# Portfolio visual palette

The site uses white and royal purple as its primary visual pair. Neutral surfaces and a restrained lavender accent keep long text readable and distinguish cards without introducing another dominant color.

| Token | Value | Use |
| --- | --- | --- |
| `--royal` | `#5121A6` | Primary buttons, links, brand mark, contact field, favicon, theme color |
| `--royal-hover` | `#3D177F` | Primary button hover |
| `--paper` | `#FFFFFF` | Main page and card surface; text on royal purple |
| `--ink` | `#241735` | Main text and dark section background |
| `--muted` | `#5D536B` | Supporting text on white or soft surfaces |
| `--soft` | `#F7F4FC` | Alternating section background |
| `--line` | `#DDD5E9` | Rules and card borders |
| `--lavender` | `#E9DDFC` | Small accents on dark surfaces and selection |
| `--dark-card` | `#35234F` | Cards within the dark section |
| `--dark-card-hover` | `#422C62` | Hover state for cards within the dark section |
| `--dark-muted` | `#DED5E8` | Supporting text on dark surfaces |

Keep body copy in ink or muted on white/soft, and use white on royal or ink. Lavender is an accent on dark surfaces, not body text on white. These pairings meet WCAG AA for normal text: royal/white 9.91:1, ink/white 16.81:1, muted/white 7.20:1, dark-muted/ink 11.84:1, and ink/lavender 12.98:1. Focus indicators use royal on light surfaces and lavender on dark surfaces.

The three "Out in the world" cards use local source imagery in equal-height, wide thumbnail frames with a subtle royal-purple lower edge. The tcworld portrait stays fully visible against royal purple. The WomenTech and Crowdin graphics are top-aligned and clipped by the frame so their original awards/episode identity and portraits remain visible while the lower employer text stays outside the displayed area. Keep the source files unedited; adjust only the CSS frame if the layout changes.
