# Design System & Visual Guidelines — Alessandro Cherchi Portfolio

> **Project Target**: Full-Stack Developer AI & Automation Portfolio
> **Design Philosophy**: Sleek, Minimalist, Cyber-Polished & Tech-Forward

---

## 1. Brand Identity & Aesthetic Persona

- **Tone**: Professional, precise, high-tech, yet restrained and clean.
- **Vibe**: Dark-mode primary with soft purple/indigo accents (`#8b8bff`), subtle glassmorphism, precise borders, and elegant 3D micro-animations.
- **Key Qualities**:
  - High contrast for readability
  - Muted glows instead of harsh neon
  - Interactive tactile feedback on hover states
  - Fluid responsiveness across all viewports

---

## 2. Color Palette & Theme Tokens

### Dark Mode (Default)
| Token | Hex / Value | Description |
| :--- | :--- | :--- |
| `--bg-primary` | `#0a0a0a` | Deep obsidian background |
| `--bg-secondary` | `#111111` | Secondary background sections |
| `--bg-card` | `#181818` | Elevated card surfaces |
| `--bg-card-hover` | `#1f1f1f` | Card hover elevation |
| `--border-subtle` | `rgba(255, 255, 255, 0.06)` | Subtle dividers & borders |
| `--border-medium` | `rgba(255, 255, 255, 0.10)` | Emphasized element outlines |
| `--text-primary` | `#f0f0f0` | High-contrast body & titles |
| `--text-secondary` | `#a0a0a0` | Muted descriptions & metadata |
| `--text-tertiary` | `#6b6b6b` | Captions & inactive items |
| `--accent` | `#8b8bff` | Signature soft lavender / indigo |
| `--accent-soft` | `rgba(139, 139, 255, 0.12)` | Subtle glow & badge background |

### Light Mode (`[data-theme="light"]`)
| Token | Hex / Value | Description |
| :--- | :--- | :--- |
| `--bg-primary` | `#f8f9fa` | Clean light grey background |
| `--bg-card` | `#ffffff` | Crisp white card surface |
| `--text-primary` | `#111111` | Dark charcoal text |
| `--accent` | `#4f46e5` | Indigo primary accent |

---

## 3. Typography & Hierarchy

- **Font Family**: `'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`
- **Headings**:
  - `h1`: Bold 48px - 64px, tight tracking (`-0.03em`), high impact hero header
  - `h2`: SemiBold 32px - 40px, section titles with subtle gradient or underline indicator
  - `h3`: Medium/SemiBold 20px - 24px, card titles
- **Body**:
  - Regular 15px - 16px, line-height 1.6 for optimum legibility.
- **Code / Tech Badges**:
  - Monospace or Inter Medium 13px, uppercase with letter-spacing for tags.

---

## 4. Components & Layout Patterns

1. **Navigation Bar**:
   - Fixed top blur navbar (`backdrop-filter: blur(12px)`)
   - Interactive 3D SVG logo with disassemble/assemble keyframe animations on hover.
2. **Cards & Containers**:
   - Border radius: `6px` (sm), `10px` (md), `14px` (lg), `18px` (xl)
   - Border: 1px solid `--border-subtle`
   - Hover transition: `0.3s ease` transform `translateY(-4px)` with subtle glow filter.
3. **Badges & Tags**:
   - Rounded pills with `--accent-soft` background and `--accent` text color.

---

## 5. Micro-Interactions & Animation Rules

- **Hover States**: All interactive elements must react within `0.2s - 0.3s` using CSS cubic-bezier or `ease`.
- **Lighting / Shadows**: Muted drop-shadows with `--accent` color for focused tech components.
- **Accessibility**: High contrast ratio maintained in both Light and Dark modes.

---

*Generated via Impeccable `/init`*
