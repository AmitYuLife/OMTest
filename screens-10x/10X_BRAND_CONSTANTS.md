# 10X Brand Constants
## Extracted from 10x.co.za for prototype development

---

## Color Palette

### Primary Colors
```css
--10x-primary-orange: #FF6B35;  /* Primary brand orange/coral */
--10x-dark: #1A1A1A;            /* Primary text */
--10x-white: #FFFFFF;           /* Backgrounds */
--10x-light-gray: #F8F8F8;      /* Secondary backgrounds */
```

### Secondary/Accent Colors
```css
--10x-medium-gray: #6B6B6B;     /* Secondary text */
--10x-light-gray-2: #E5E5E5;    /* Borders, dividers */
--10x-success-green: #00C48C;    /* Positive growth */
--10x-warning-red: #FF4757;      /* Negative/alerts */
```

### Yu Brand Colors (for co-branding)
```css
--yu-pink: #E30D76;              /* Yu primary */
--yu-purple: #6B2D8F;            /* Yu secondary */
```

---

## Typography

### Font Families
Primary: Clean, modern sans-serif (similar to Inter, Helvetica, or system fonts)
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
```

### Font Sizes
- Hero: 32-36px
- H1: 28px
- H2: 24px
- H3: 20px
- Body Large: 18px
- Body: 16px
- Body Small: 14px
- Caption: 12px

### Font Weights
- Regular: 400
- Medium: 500
- Semibold: 600
- Bold: 700

---

## Branding Elements

### Logo Treatment
**Format**: "10X ❤️ Yu" or "10X powered by Yu"
- 10X logo: Simple, bold typography
- Heart separator: ❤️
- Yu square: Pink (#E30D76) with white "Yu" text

### Co-branding Hierarchy
1. 10X is primary brand (larger, more prominent)
2. Yu is secondary (subtle but visible)
3. Heart separator shows partnership

---

## Design Principles (from website)

### 1. Simplicity
- Clean, minimal layouts
- Generous white space
- Clear visual hierarchy
- No unnecessary decoration

### 2. Transparency
- Clear data visualization
- Prominent fee information
- Easy-to-understand language
- No hidden elements

### 3. Modern & Tech-Forward
- Contemporary design patterns
- Digital-first aesthetic
- Smooth interactions
- Mobile-optimized

### 4. Professional & Approachable
- Not stuffy or corporate
- Warm but professional
- Confident but humble
- Data-driven

---

## UI Components Style

### Buttons
- Primary: Orange background (#FF6B35), white text
- Secondary: White background, orange border
- Text: Orange text, no background
- Border radius: 8px (medium), 24px (pill)
- Padding: 16px 24px

### Cards
- Background: White
- Border radius: 12-16px
- Shadow: Subtle (0 2px 8px rgba(0,0,0,0.08))
- Padding: 20-24px

### Colors for Data
- Positive/Growth: Green (#00C48C)
- Negative/Loss: Red (#FF4757)
- Neutral: Gray (#6B6B6B)
- Primary value: Orange (#FF6B35)

### Icons
- Style: Line icons (not filled)
- Weight: 1.5-2px stroke
- Size: 20-24px standard
- Color: Match text or use orange for emphasis

---

## Key Messaging Themes

### Headlines/CTAs
- "10X your future"
- "Simple. Transparent. Low fees."
- "Every Rand counts"
- "Smart investing made easy"
- "You're saving R[X] in fees"

### Tone
- Direct and honest
- No jargon
- Empowering
- Confident
- Warm but professional

---

## Differences from Old Mutual

| Element | Old Mutual | 10X |
|---------|-----------|-----|
| **Primary color** | Green (#76B657) | Orange (#FF6B35) |
| **Feel** | Traditional, warm, heritage | Modern, clean, tech-forward |
| **Emphasis** | Relationship, trust | Fees, transparency |
| **Typography** | Bariol (custom) | System sans-serif |
| **Complexity** | More elements | Minimal |
| **Shadow depth** | Moderate | Light |

---

## Quick Replace Guide

### Global Find & Replace
```
"Old Mutual" → "10X"
"#76B657" → "#FF6B35" (green to orange)
"pension" → "retirement savings"
"Your pension" → "Your 10X retirement savings"
"SuperFund" → "Umbrella Fund"
```

### CSS Variables to Update
```css
/* OLD - Old Mutual */
--om-green: #76B657;
--om-dark-green: #5A9142;

/* NEW - 10X */
--10x-primary: #FF6B35;
--10x-primary-dark: #E55A2B;
```

---

## Screen-Specific Changes

### Hero Sections
- Background: Orange (#FF6B35) instead of green
- Keep white text for contrast
- Simpler illustration style (more geometric)

### Value Cards
- Add "Fee savings" prominent callout
- Use orange accent for primary values
- Green for growth/positive changes

### CTAs
- Orange buttons (primary actions)
- White/outlined buttons (secondary)
- Bold, direct copy

---

*Reference: www.10x.co.za - Extracted Feb 2026*
