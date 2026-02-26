# LLmao — Style Guide

This document defines the visual foundations of LLmao.
Its goal is consistency, not creativity for creativity’s sake.

If a design choice increases clarity, predictability, or emotional safety, it is correct.
If it adds noise, novelty, or performance, it is wrong.

---

## 1. Color Palette

The palette is calm, grounded, and human.
No neon. No dating-app gradients. No dopamine colors.

### Primary Colors

**Primary / Trust Blue**
- Hex: `#2563EB`
- Usage: Primary CTAs, links, focus states
- Rationale: Conveys trust, clarity, and confidence without feeling corporate

**Primary Dark**
- Hex: `#1E40AF`
- Usage: Hover states, emphasized text

---

### Secondary Colors

**Soft Slate**
- Hex: `#64748B`
- Usage: Secondary text, labels, metadata

**Muted Indigo**
- Hex: `#6366F1`
- Usage: Subtle accents, icons, section dividers

---

### Background Colors

**Primary Background**
- Hex: `#FFFFFF`
- Usage: Main page background

**Soft Neutral**
- Hex: `#F8FAFC`
- Usage: Cards, section backgrounds, callouts

**Border / Divider**
- Hex: `#E5E7EB`
- Usage: Card borders, separators

---

### Text Colors

**Primary Text**
- Hex: `#0F172A`
- Usage: Headlines, body copy

**Secondary Text**
- Hex: `#475569`
- Usage: Supporting copy, helper text

**Muted Text**
- Hex: `#94A3B8`
- Usage: Footnotes, captions

---

### Status Colors (Use Sparingly)

**Success**
- Hex: `#16A34A`

**Warning**
- Hex: `#F59E0B`

**Error**
- Hex: `#DC2626`

Status colors should never be used decoratively.

---

## 2. Typography

Typography should feel neutral, modern, and invisible.
The copy should do the emotional work — not the font.

### Font Stack

**Primary Font**
- `Inter`
- Fallback: `system-ui, -apple-system, BlinkMacSystemFont, sans-serif`

Why Inter:
- Highly readable at small sizes
- Neutral personality
- Widely supported

---

### Type Scale

| Element | Size | Weight | Line Height |
|------|------|--------|-------------|
| H1 | 40px | 700 | 1.2 |
| H2 | 32px | 600 | 1.25 |
| H3 | 24px | 600 | 1.3 |
| Body | 16px | 400 | 1.55 |
| Small | 14px | 400 | 1.45 |
| Caption | 12px | 400 | 1.4 |

Rules:
- Never use ultra-bold (800+) for marketing emphasis
- Never compress line height to “look cool”
- Readability > density

---

## 3. Visual Tone

**One-sentence definition:**

> Calm, structured, and human — reducing anxiety instead of creating excitement.

### Keywords
- Predictable
- Grounded
- Warm
- Clear
- Low-pressure

### Avoid
- Playful gimmicks
- Flashy animations
- “Startup hype” aesthetics
- Dating-app visual language

If something feels like it’s trying too hard, it’s wrong.

---

## 4. Component Patterns

Components should feel familiar and safe.
Nothing should surprise the user visually.

---

### Buttons

**Primary Button**
- Background: `#2563EB`
- Text: `#FFFFFF`
- Border Radius: `8px`
- Padding: `12px 20px`
- Font Weight: 500

Hover:
- Background: `#1E40AF`

Disabled:
- Background: `#CBD5E1`
- Text: `#FFFFFF`

Primary buttons are for commitment actions only:
- “Get early access”
- “Join this hang”

---

**Secondary Button**
- Background: Transparent
- Border: `1px solid #CBD5E1`
- Text: `#2563EB`

Used for:
- “Preview upcoming hangs”
- Non-commitment actions

---

### Cards

- Background: `#FFFFFF`
- Border: `1px solid #E5E7EB`
- Border Radius: `12px`
- Padding: `20px`
- Shadow: `0 1px 2px rgba(0,0,0,0.04)`

Cards should:
- Group information
- Reduce cognitive load
- Never feel decorative

---

### CTAs

CTA copy should be:
- Direct
- Reassuring
- Non-salesy

Good:
- “Get early access”
- “Preview upcoming hangs”

Bad:
- “Join the movement”
- “Level up your social life”
- “Find your tribe”

---

## 5. Spacing & Layout

- Default spacing unit: `8px`
- Section padding: `64px` (desktop), `40px` (mobile)
- Max content width: `1100px`

Whitespace is a feature.
Crowded layouts increase anxiety.

---

## 6. Motion & Interaction

Motion should explain, not entertain.

Rules:
- No auto-playing animations
- No bouncing, pulsing, or looping effects
- Transitions ≤ 200ms, ease-out

Allowed:
- Subtle hover states
- Simple fade-ins for modals

---

## 7. Accessibility

- Minimum contrast ratio: WCAG AA
- Click targets ≥ 44px
- Never rely on color alone to convey meaning

Accessibility = emotional safety.

---

## Final Principle

If you’re deciding between:
- Slightly boring but clear  
- Slightly cool but ambiguous  

Always choose **clear**.

LLmao’s job is not to impress.
It’s to make showing up feel easier.