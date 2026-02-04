# Visual Layout Guide: Screen D
## Employee Exit Journey - Section-by-Section Breakdown

---

## 📱 Screen Overview (375px × ~1400px)

```
┌─────────────────────────────────────┐
│         HEADER (92px)               │  ← Old Mutual ❤️ Yu branding
├─────────────────────────────────────┤
│                                     │
│      HERO SECTION (260px)           │  ← Teal background, empathetic
│      "You're leaving your employer" │
│                                     │
├─────────────────────────────────────┤
│  DESCRIPTION CARD (overlap)         │  ← Benefits don't leave you
├─────────────────────────────────────┤
│                                     │
│  INFO BOX (green)                   │  ← What happens next?
│                                     │
├─────────────────────────────────────┤
│                                     │
│  PROTECTED ITEMS SECTION            │  ← What you've built so far
│  • Your Pension                     │
│  • Life Cover                       │
│  • Disability Cover                 │
│                                     │
├─────────────────────────────────────┤
│                                     │
│  SECTION TITLE                      │  ← "Choose what works for you"
│                                     │
├─────────────────────────────────────┤
│                                     │
│  ╔═══════════════════════════════╗ │
│  ║ OPTION 1: STAY (Green)        ║ │  ← RECOMMENDED
│  ║ [Radio Selected]              ║ │
│  ║ ✓ Keep pension                ║ │
│  ║ ✓ Continue cover              ║ │
│  ║ ✓ Adviser stays               ║ │
│  ║ ✓ No paperwork                ║ │
│  ║ ❤️ MEMBER-FOR-LIFE            ║ │
│  ╚═══════════════════════════════╝ │
│                                     │
│  ┌───────────────────────────────┐ │
│  │ OPTION 2: CASH OUT (Yellow)   │ │  ← WARNING
│  │ [Radio Empty]                 │ │
│  │ ✗ Up to 36% tax               │ │
│  │ ✗ Lose cover                  │ │
│  │ ✗ Reduced retirement          │ │
│  │ ⚠️ Most people regret...      │ │
│  └───────────────────────────────┘ │
│                                     │
│  ┌───────────────────────────────┐ │
│  │ OPTION 3: TRANSFER (Gray)     │ │  ← NEUTRAL
│  │ [Radio Empty]                 │ │
│  │ ✓ Keep pension                │ │
│  │ ✗ Lose cover                  │ │
│  │ ✗ New underwriting            │ │
│  │ ✗ Extra paperwork             │ │
│  └───────────────────────────────┘ │
│                                     │
├─────────────────────────────────────┤
│                                     │
│  SUPPORT SECTION                    │  ← Need help? Adviser available
│                                     │
├─────────────────────────────────────┤
│                                     │
│  [CONTINUE WITH OLD MUTUAL]         │  ← Primary CTA button
│                                     │
└─────────────────────────────────────┘
```

---

## Section 1: Header (92px height)

```
┌─────────────────────────────────────────────────────────┐
│  ☰  🔔         🏢 OLD MUTUAL ❤️ 💗         2,502 🪙    │
│                     (centered)               (right)    │
└─────────────────────────────────────────────────────────┘
```

**Layout**:
- **Left**: Hamburger menu + notification bell (24px icons)
- **Center**: Old Mutual logo + heart separator + Yu square logo
- **Right**: YuCoin count + coin icon
- **Background**: White
- **Shadow**: 0px 4px 24px rgba(0,0,0,0.08)
- **Radius**: 0 0 40px 40px (rounded bottom corners)

**Colors**:
- Background: `#FFFFFF`
- Icons: `#1A1A1A`
- Text: `#1A1A1A`
- Yu accent: `#E30D76`

---

## Section 2: Hero Section (260px height)

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║                                              [Illustration]║
║                                              (faded)      ║
║  🏢 OLD MUTUAL                                            ║
║                                                           ║
║  You're leaving                                           ║
║  your employer                                            ║
║                                                           ║
╚═══════════════════════════════════════════════════════════╝
```

**Layout**:
- **Logo**: Small Old Mutual logo (white, 112px wide)
- **Title**: "You're leaving your employer"
  - Font: Bariol Bold, 28px
  - Color: White
  - Line height: 32px
  - Max width: 250px (wraps)
- **Illustration**: Right side, subtle, decorative (optional)

**Colors**:
- Background: `#429479` (Old Mutual Primary Teal)
- Text: `#FFFFFF`
- Logo: `#FFFFFF`

**Why Teal?** Calmer than green—appropriate for transition moment.

---

## Section 3: Description Card (Overlap)

```
┌───────────────────────────────────────────────────────────┐
│                                                           │
│  Your benefits don't have to leave you. Keep your        │
│  pension and protection with Old Mutual.                 │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

**Layout**:
- **Position**: Overlaps hero by 8px (margin-top: -8px)
- **Padding**: 24px
- **Text**: Bold, 16px, line-height 20px

**Colors**:
- Background: `#FAFAFE` (Neutral/5)
- Border: 1px solid `#E3E3E1`
- Text: `#1A1A1A`
- Radius: 0 0 16px 16px (continues from hero)

---

## Section 4: Info Box (Green Alert)

```
┌───────────────────────────────────────────────────────────┐
│  ┌───┐                                                    │
│  │ i │  What happens next?                               │
│  └───┘  You have options for your pension and risk       │
│         cover. Take your time to choose what works       │
│         best for you.                                     │
└───────────────────────────────────────────────────────────┘
```

**Layout**:
- **Icon**: 32px circle, `#76B657` background, white "i"
- **Title**: Bold, 16px, "What happens next?"
- **Body**: Regular, 14px, supportive copy
- **Padding**: 20px
- **Gap**: 16px (icon to content)

**Colors**:
- Background: `#ECF9EE` (Success/10 - light green)
- Border: 1px solid `#76B657`
- Icon: `#76B657` with white text
- Text: `#1A1A1A` (title), `#464647` (body)
- Radius: 16px

---

## Section 5: Protected Items Section

```
┌───────────────────────────────────────────────────────────┐
│  What you've built so far                                │
│                                                           │
│  ┌─────────────────────────────────────────────────────┐ │
│  │ ┌───┐  YOUR PENSION                                 │ │
│  │ │💰│  R75 193,54                                     │ │
│  │ └───┘                                                │ │
│  └─────────────────────────────────────────────────────┘ │
│                                                           │
│  ┌─────────────────────────────────────────────────────┐ │
│  │ ┌───┐  LIFE COVER                                   │ │
│  │ │🛡️│  R850,000                                      │ │
│  │ └───┘                                                │ │
│  └─────────────────────────────────────────────────────┘ │
│                                                           │
│  ┌─────────────────────────────────────────────────────┐ │
│  │ ┌───┐  DISABILITY COVER                             │ │
│  │ │💚│  R425,000                                       │ │
│  │ └───┘                                                │ │
│  └─────────────────────────────────────────────────────┘ │
└───────────────────────────────────────────────────────────┘
```

**Layout**:
- **Container**: White card, 1px `#E3E3E1` border, 16px radius
- **Title**: Bold, 16px, "What you've built so far"
- **Items**: 3 rows, each with:
  - Icon: 40×40px square, 8px radius, `#76B657` background
  - Label: 12px uppercase, `#A0A09B`
  - Value: 16px bold, `#1A1A1A`
- **Item background**: `#FAFAFE`
- **Padding**: 20px container, 12px items
- **Gap**: 12px between items

**Icons**:
- Pension: 💰 (money bag)
- Life: 🛡️ (shield)
- Disability: 💚 (green heart)

---

## Section 6: Choice Cards (THE CRITICAL SECTION)

### Section Title:

```
Choose what works for you
```

**Style**: Bold, 20px, `#1A1A1A`, letter-spacing 0.8px

---

### Option 1: Stay with Old Mutual (RECOMMENDED)

```
╔═══════════════════════════════════════════════════════╗
║  ✓ RECOMMENDED                              ⦿        ║
║                                          (selected)   ║
║  ┌───┐                                               ║
║  │🏠│  Stay with Old Mutual                          ║
║  └───┘  Member-for-Life protection                   ║
║                                                       ║
║  ✓ Keep your full pension value                      ║
║  ✓ Continue your life & disability cover             ║
║  ✓ Your adviser stays with you                       ║
║  ✓ No paperwork, seamless transition                 ║
║                                                       ║
║  [❤️ MEMBER-FOR-LIFE]                                ║
╚═══════════════════════════════════════════════════════╝
```

**Visual Treatment**:
- **Border**: 2px solid `#76B657` (green)
- **Background**: Linear gradient `#ECF9EE` → `#FFFFFF` (135°)
- **Badge**: "✓ RECOMMENDED" white on `#76B657`, top-left
- **Radio**: Filled circle with checkmark, top-right
- **Icon**: 48×48px square, 12px radius, `#76B657`, 🏠 emoji
- **Title**: "Stay with Old Mutual" (Bold, 18px)
- **Subtitle**: "Member-for-Life protection" (Regular, 12px, gray)
- **Benefits**: 4 items with green check icons (20px circles)
- **Member Badge**: Gradient `#E30D76` → `#C90B64`, white text, ❤️ icon

**Layout**:
- Padding: 20px
- Gap: 12px between elements
- Radio: Absolute position top-right

---

### Option 2: Cash Out (WARNING)

```
┌───────────────────────────────────────────────────────┐
│                                              ○        │
│                                          (empty)     │
│  ┌───┐                                               │
│  │💸│  Cash out                                      │
│  └───┘  Take your money now                          │
│                                                       │
│  ✗ Up to 36% lost to tax                             │
│  ✗ Lose your life & disability cover                 │
│  ✗ Retirement savings reduced                        │
│                                                       │
│  ┌─────────────────────────────────────────────────┐ │
│  │ ⚠️ Most people who cash out wish they hadn't.  │ │
│  │ R75k today could be worth R450k+ at retirement. │ │
│  └─────────────────────────────────────────────────┘ │
└───────────────────────────────────────────────────────┘
```

**Visual Treatment**:
- **Border**: 2px solid `#FFD600` (yellow warning)
- **Background**: `#FFFFFF`
- **No Badge**: Absence signals "not recommended"
- **Radio**: Empty circle, gray border, top-right
- **Icon**: 48×48px, `#FFD600`, 💸 emoji (money flying away)
- **Consequences**: 3 items with gray X icons (20px circles)
- **Warning Box**: 
  - Background: `rgba(255, 214, 0, 0.1)` (10% yellow)
  - Border: 1px solid `#FFD600`
  - Text: Bold, 12px, `#464647`
  - Contains social proof + concrete numbers

**Psychology**: 
- Yellow = caution, not prohibition
- X icons = clear about consequences
- Social proof > fear tactics
- Concrete numbers (R75k → R450k+) create anchoring

---

### Option 3: Transfer to Another Fund (NEUTRAL)

```
┌───────────────────────────────────────────────────────┐
│                                              ○        │
│                                          (empty)     │
│  ┌───┐                                               │
│  │📤│  Transfer to another fund                      │
│  └───┘  Move to a different provider                 │
│                                                       │
│  ✓ Keep your pension value                           │
│  ✗ Lose your current life & disability cover         │
│  ✗ May require new medical underwriting              │
│  ✗ Additional paperwork required                     │
│                                                       │
└───────────────────────────────────────────────────────┘
```

**Visual Treatment**:
- **Border**: 2px solid `#E3E3E1` (neutral gray)
- **Background**: `#FFFFFF`
- **No Badge**: Neutral option
- **Radio**: Empty circle, gray border
- **Icon**: 48×48px, `#E3E3E1`, 📤 emoji (outbox)
- **Mixed List**: 1 green check, 3 gray X icons
- **Honest**: Shows both positive and negative

**Psychology**:
- Not demonized, but not ideal
- Transparent about drawbacks
- Respects member autonomy

---

## Section 7: Support Section

```
┌───────────────────────────────────────────────────────────┐
│  ┌───┐                                                    │
│  │👤│  Need help deciding?                               │
│  └───┘  Your adviser is here to guide you through your   │
│         options at no extra cost.                         │
└───────────────────────────────────────────────────────────┘
```

**Layout**:
- **Icon**: 48px circle, white background, 2px `#E3E3E1` border, 👤 emoji
- **Title**: Bold, 14px, "Need help deciding?"
- **Body**: Regular, 12px, `#A0A09B`
- **Padding**: 20px
- **Gap**: 16px

**Colors**:
- Background: `#FAFAFE`
- Border: 1px solid `#E3E3E1`
- Text: `#1A1A1A` (title), `#A0A09B` (body)
- Radius: 16px

**Message**: Channel-supportive, emphasizes "no extra cost" to reduce friction.

---

## Section 8: Primary CTA Button

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║            Continue with Old Mutual                       ║
║                                                           ║
╚═══════════════════════════════════════════════════════════╝
```

**Specs**:
- **Width**: 328px (full width of content area)
- **Height**: 56px (16px padding top/bottom + 24px line-height)
- **Text**: "Continue with Old Mutual"
  - Bold, 16px, white
  - Letter-spacing: 0.6px
- **Background**: `#76B657` (green)
- **Shadow**: 0px 4px 0px `rgba(66, 148, 121, 0.3)` (3D effect)
- **Radius**: 16px

**States**:
- **Default**: Green background, 4px shadow below
- **Hover**: Darker green (`#5BA348`), lift up 2px, deeper shadow
- **Active**: Push down 2px, shallower shadow
- **Disabled**: Gray, 50% opacity, no shadow

**Why this copy?** Reinforces the recommended choice without being pushy.

---

## 📐 Spacing System

### Vertical Spacing (Top to Bottom):

```
Header: 0px top
Hero: 0px top (continues from header)
Description: -8px top (overlaps hero)
↓ 32px gap
Info Box
↓ 24px gap
Protected Items
↓ 24px gap
Section Title
↓ 16px gap
Choice Card 1
↓ 16px gap
Choice Card 2
↓ 16px gap
Choice Card 3
↓ 24px gap
Support Section
↓ 24px gap
CTA Button
↓ 40px bottom padding
```

### Horizontal Spacing:

- **Container**: 375px total width
- **Content padding**: 24px left/right
- **Content width**: 327px (375 - 48)
- **Cards width**: 327px
- **Internal padding**: 20px (cards), 16px (smaller elements)

### Internal Element Gaps:

- **Major sections**: 32px
- **Minor sections**: 24px
- **Cards**: 16px
- **Within cards**: 12px
- **Icon to text**: 8px-16px
- **Badge to title**: 12px

**Everything follows 8px grid**: 8, 16, 24, 32, 40, 48, etc.

---

## 🎨 Color Palette Quick Reference

### Primary Colors:
| Color | Hex | Usage |
|-------|-----|-------|
| OM Dark | `#1A1A1A` | Body text, titles |
| OM Primary (Teal) | `#429479` | Hero background |
| OM Secondary (Green) | `#76B657` | Recommended, CTAs, positive |
| Yu Brand (Pink) | `#E30D76` | Member badge gradient start |

### Secondary Colors:
| Color | Hex | Usage |
|-------|-----|-------|
| Warning Yellow | `#FFD600` | Cash out warning |
| Success Light | `#ECF9EE` | Info box background |
| Neutral Background | `#FAFAFE` | Cards, items |
| Neutral Border | `#E3E3E1` | Borders, dividers |

### Text Colors:
| Color | Hex | Usage |
|-------|-----|-------|
| Strong | `#1A1A1A` | Headlines, important text |
| Body | `#464647` | Body copy |
| Subtle | `#A0A09B` | Labels, secondary text |
| White | `#FFFFFF` | On dark backgrounds |

---

## 📏 Typography Scale

| Element | Font | Size | Weight | Line Height | Usage |
|---------|------|------|--------|-------------|-------|
| Hero Title | Bariol | 28px | 700 | 32px | "You're leaving..." |
| Section Title | Bariol | 20px | 700 | 24px | "Choose what works..." |
| Card Title | Bariol | 18px | 700 | 24px | "Stay with Old Mutual" |
| Description | Bariol | 16px | 700 | 20px | Description card text |
| Body | Bariol | 14px | 400 | 20px | Body copy, benefits |
| Label | Bariol | 12px | 400/700 | 16px | Labels, subtitles |
| Badge | Bariol | 10px | 700 | 12px | "RECOMMENDED", etc. |

---

## 🔘 Interactive Elements

### Radio Buttons:

```
Unselected:          Selected (Option 1):
    ○                      ⦿
 24px circle          24px circle
 2px #E3E3E1         Fill #76B657
 Empty center        White checkmark ✓
```

### Check/X Icons:

```
Check (Positive):    X (Negative):
    ✓                    ✗
 20px circle         20px circle
 Fill #76B657        Fill #E3E3E1
 White ✓             Gray ✗ (#A0A09B)
```

### Badges:

```
Recommended:         Member-for-Life:
 ✓ RECOMMENDED        ❤️ MEMBER-FOR-LIFE
 Fill #76B657        Gradient #E30D76→#C90B64
 White text          White text
 6px padding         6px padding
 12px radius         12px radius
```

---

## 📱 Responsive Behavior (375px Mobile)

### Scrolling:
- **Header**: Fixed at top (sticky)
- **Content**: Scrollable
- **CTA**: Could be fixed at bottom (optional)

### Touch Targets:
- **Minimum**: 44×44px for all interactive elements
- **Cards**: Entire card is tappable (not just radio)
- **Radio circles**: 24px visible, 44px tap area
- **Button**: 328×56px (well above minimum)

### Keyboard Navigation:
- Tab order: Header → Info → Choice 1 → Choice 2 → Choice 3 → Support → CTA
- Arrow keys: Navigate between radio options
- Enter/Space: Select choice
- Focus ring: Blue outline (not shown in mockup, but should exist)

---

## 🎯 Visual Hierarchy Priority

**What the eye sees first:**

1. **Hero Title** (28px, white on teal, top) → "You're leaving..."
2. **Green Card** (largest, brightest, center) → Option 1
3. **Member Badge** (gradient, bottom of Option 1) → ❤️ MEMBER-FOR-LIFE
4. **CTA Button** (green, bottom, large) → Continue
5. **Protected Items** (shows value at risk)
6. **Yellow Warning** (Option 2, cautionary)
7. **Support Section** (helper, near bottom)

**Why this order?**
- Sets emotional context (hero)
- Makes recommended choice obvious (green)
- Reinforces brand positioning (badge)
- Provides clear action (CTA)
- Shows value context (protected items)
- Warns gently (yellow option)
- Offers help (support)

---

## 🖼️ Asset List for Implementation

### Required Assets:

**Logos:**
- [ ] Old Mutual logo (white version for hero)
- [ ] Old Mutual logo (dark version for header)
- [ ] Yu square logo (pink/magenta)

**Icons:**
- [ ] Hamburger menu icon
- [ ] Notification bell icon
- [ ] YuCoin icon
- [ ] Info icon (can be text "i" in circle)
- [ ] Check icon (can be text "✓" in circle)
- [ ] X icon (can be text "✗" in circle)

**Emoji/Illustrations:**
- [ ] 🏠 Home icon (or custom SVG)
- [ ] 💸 Money flying away (or custom SVG)
- [ ] 📤 Outbox/transfer (or custom SVG)
- [ ] 💰 Money bag (or custom SVG)
- [ ] 🛡️ Shield (or custom SVG)
- [ ] 💚 Green heart (or custom SVG)
- [ ] 👤 Person/adviser (or custom SVG)
- [ ] ⚠️ Warning triangle (or custom SVG)
- [ ] ❤️ Yu heart (text emoji okay)

**Optional:**
- [ ] Hero background illustration (circles/abstract)
- [ ] Piggy bank illustration (from existing screen)

---

## ✅ Pre-Flight Checklist

Before considering this screen "done":

**Design**:
- [ ] All colors match brand palette
- [ ] All fonts use Bariol (or fallback)
- [ ] All spacing follows 8px grid
- [ ] All touch targets ≥ 44px
- [ ] All text is legible (WCAG AA contrast)

**Content**:
- [ ] Copy is empathetic, not salesy
- [ ] No jargon or complex terms
- [ ] South African Rand formatting (R) correct
- [ ] Adviser language is supportive
- [ ] Member-for-Life positioning clear

**Functionality**:
- [ ] Radio buttons work (only one selected)
- [ ] Cards respond to interaction
- [ ] Button has hover/active states
- [ ] Scrolling works smoothly
- [ ] Focus states exist for keyboard users

**Integration**:
- [ ] Matches existing Old Mutual design system
- [ ] Reuses components from other screens
- [ ] Fits into 8-screen concept flow
- [ ] Data hooks identified for API

---

*Visual guide created: February 3, 2026*  
*Screen: D - Employee Exit Journey*  
*Dimensions: 375px × ~1400px*  
*Status: Ready for Figma implementation*

**Use this guide as a reference while building in Figma. Every measurement, color, and element is specified above.** 📐
