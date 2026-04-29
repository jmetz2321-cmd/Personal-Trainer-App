# JAM Design System
## Apple-Inspired Clean Design - Premium + Minimalist

JAM is a modern, premium design system inspired by Apple's design language. It balances minimalism with clarity, focusing on content and usability above visual flourish. Built for fitness apps, wellness platforms, and lifestyle tools that prioritize elegance and simplicity.

**Theme:** Clean, light interface with system blue accents. Generous whitespace. Subtle interactions. Premium feel.

---

## Color Palette

### Primary Colors (Light Mode)
| Color | Hex | Usage | Vibe |
|-------|-----|-------|------|
| **System Blue** | `#007AFF` | CTAs, highlights, active states | Apple's signature blue, trustworthy |
| **White Background** | `#FFFFFF` | Cards, primary surfaces | Clean, modern, premium |
| **Light Gray Background** | `#F9F9F9` | Main app background | Subtle, breathing room |
| **Dark Text** | `#000000` | Primary text, headers | High contrast, readable |

### Accent Colors
| Color | Hex | Usage |
|-------|-----|-------|
| **Secondary Text** | `#666666` | Body text, descriptions |
| **Tertiary Text** | `#999999` | Labels, helper text, disabled states |
| **Border Gray** | `#E5E5EA` | Lines, dividers, subtle separators |
| **Success Green** | `#34C759` | Achievement, recovery, positive states |
| **Alert Red** | `#FF3B30` | Warnings, high intensity, alerts |

### Subtle Shadows
- **Card Shadow:** `0 4px 12px rgba(0, 122, 255, 0.1)` - On hover, adds subtle depth
- **Focus Ring:** `0 0 0 3px rgba(0, 122, 255, 0.1)` - On input focus, shows interactive state
- **Minimal:** Shadows are barely visible, never dominant

---

## Typography

### Font Stack
```
Font Family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', sans-serif
```
Uses system fonts for native feel on all platforms.

| Element | Size | Weight | Line Height | Letter Spacing |
|---------|------|--------|-------------|-----------------|
| **H1** (Page Titles) | 32px | 700 Bold | 1.2 | -0.5px |
| **H2** (Section Headers) | 20px | 600 Semi-Bold | 1.3 | -0.3px |
| **Subtitle** | 16px | 400 Regular | 1.4 | 0px |
| **Body Text** | 15px | 400 Regular | 1.5 | 0px |
| **Small Text** | 13px | 400 Regular | 1.5 | 0.25px |
| **Labels** | 13px | 600 Semi-Bold | 1.4 | 0.5px |
| **Button Text** | 15px | 600 Semi-Bold | 1.4 | -0.3px |

---

## Spacing System

**Base Unit: 8px**

| Name | Value | Use |
|------|-------|-----|
| **XS** | 4px | Micro spacing, icon padding |
| **SM** | 8px | Compact spacing, button padding |
| **MD** | 16px | Standard spacing, section padding |
| **LG** | 24px | Large spacing, section separation |
| **XL** | 32px | Extra large spacing, major sections |
| **2XL** | 48px | Screen padding, major layout gaps |

---

## Components

### Buttons

**Primary Button**
```
Background: #007AFF (System Blue)
Text: White, 15px Semi-Bold
Padding: 12px 20px
Border Radius: 8px
Interaction: Active state reduces opacity to 0.8
Shadow: Subtle, removed on interaction
```

**Secondary Button**
```
Background: #E5E5EA
Text: #007AFF, 15px Semi-Bold
Padding: 12px 20px
Border: None
Border Radius: 8px
Interaction: Active state reduces opacity
```

### Cards
```
Background: #FFFFFF
Border: 1px solid #E5E5EA
Border Radius: 12px
Padding: 16px
Shadow: None (or minimal 0 4px 12px rgba(0,122,255,0.1) on hover)
Hover: Border changes to #007AFF, subtle blue glow
```

### Input Fields
```
Background: #FFFFFF
Border: 1px solid #E5E5EA
Border Radius: 8px
Padding: 12px 16px
Focus: Border #007AFF, focus ring 0 0 0 3px rgba(0,122,255,0.1)
Text: #000000
```

### Range Sliders
```
Track: #E5E5EA
Thumb: #007AFF
Thumb Size: 28px (Apple-style larger touch target)
Track Height: 4px
Hover Thumb: Scale 1.1
Shadow on Thumb: 0 2px 8px rgba(0,122,255,0.3)
```

### Status Labels
```
Good State: Green (#34C759) text on light green background
Warning State: Orange (#FF9500) text on light orange background
Alert State: Red (#FF3B30) text on light red background
Backgrounds use 10% opacity of the color
```

---

## Icons & Imagery

- **Style:** Minimalist line icons (2px stroke)
- **Size:** 24px standard, 32px large, 16px small
- **Color:** Match context (#FFA500 for primary, #1A1A2E for neutral)
- **Imagery:** Clean, bright photos with breathing room; avoid cluttered backgrounds

---

## Spacing & Layout

- **Mobile Padding:** 16px (all edges)
- **Card Margin:** 12px between stacked elements
- **Section Gap:** 24px between major sections
- **Header Height:** 56px (iOS-style safe area)
- **Max Width:** 100% on mobile, 480px on tablet, 600px on desktop

---

## Animation & Interaction

Animations in JAM are **subtle and brief**. Focus is on feeling responsive, not flashy.

| Animation | Duration | Easing | Use |
|-----------|----------|--------|-----|
| **Button Press** | 150ms | ease-out | Opacity change, scale 0.98 |
| **Hover Transition** | 200ms | ease-in-out | Border color, shadow changes |
| **Slider Movement** | 100ms | ease-out | Real-time form input updates |
| **Border Color Change** | 200ms | ease-in-out | Focus, hover states |
| **Scale Effect** | 150ms | ease-out | Interactive elements on hover |

**Philosophy:** Interactions should feel instant but not jarring. Avoid long animations.

---

## Dark Mode (Optional Future)

If implementing dark mode, follow this approach:
- Background White → #1A1A1A
- Text Primary (#000) → #F5F5F5
- Cards White → #252525
- Inputs → #333333
- Dividers → #444444
- Keep System Blue (#007AFF) as accent (Apple uses same blue in dark mode)

*Note: Current JAM primary is light mode. Dark mode follows same minimalist Apple approach.*

---

## Usage Guidelines

1. **Color:** Use System Blue (#007AFF) for CTAs and highlights. Keep color minimal—let content shine.
2. **Whitespace:** Generous spacing between elements. Empty space is not wasted—it's breathing room.
3. **Shadows:** Keep them subtle. Almost invisible unless hovering. Never dark or dramatic.
4. **Text:** Use system fonts. Trust the typography hierarchy. Avoid custom fonts.
5. **Consistency:** Follow the spacing grid. Use 4px, 8px, 16px, 24px, 32px spacing.
6. **Accessibility:** 4.5:1 contrast ratio for text. Touch targets minimum 44px. Focus states visible.
7. **Interactions:** Subtle and responsive. Spring animations feel alive without being distracting.
8. **Focus:** Content first, interface supports. Never distract from the message.

## Core Principle

**JAM is Apple-inspired design: Minimalist, premium, elegant. The interface disappears. Content shines. Every pixel has purpose.**

Built for humans who value clarity over complexity. Every element earns its place.
