# Drone Daddy Iowa: Branding

Source: `styles.css` in github.com/Shamanlo/drone-daddy-iowa (site: dronedaddyiowa.com)

## Fonts (Google Fonts)

```
https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Archivo:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500&display=swap
```

| Role | Font | Fallback |
|---|---|---|
| Display (headlines) | Abril Fatface | Georgia, serif |
| Body | Archivo 400/500/600/700 | "Helvetica Neue", Arial, sans-serif |
| Mono (labels, accents) | IBM Plex Mono 400/500 | "Courier New", monospace |

## Colors

| Name | Value | Use |
|---|---|---|
| Green | `#4E6B45` | Primary brand green |
| Green deep | `#3A5234` | Darker green |
| Scrim | `#121E14` | Near-black green overlay |
| Cream | `#F4E8D0` | Light text on dark |
| Cream dim | `rgba(244,232,208,.68)` | Secondary light text |
| Cream line | `rgba(244,232,208,.22)` | Borders, dividers |
| Paper | `#F7F2E6` | Light page background |
| Ink | `#1E2A20` | Main dark text |
| Ink soft | `#45564A` | Secondary dark text |

## Other tokens

- Corner radius: 10px
- Max content width: 1160px

## CSS variables

```css
:root{
  --green:      #4E6B45;
  --green-deep: #3A5234;
  --scrim:      #121E14;
  --cream:      #F4E8D0;
  --cream-dim:  rgba(244,232,208,.68);
  --cream-line: rgba(244,232,208,.22);
  --paper:      #F7F2E6;
  --ink:        #1E2A20;
  --ink-soft:   #45564A;
  --radius: 10px;
  --wrap: 1160px;
  --font-display: "Abril Fatface", Georgia, serif;
  --font-body: "Archivo", "Helvetica Neue", Arial, sans-serif;
  --font-mono: "IBM Plex Mono", "Courier New", monospace;
}
```

## Not yet captured

- Logo files (none in the repo)
