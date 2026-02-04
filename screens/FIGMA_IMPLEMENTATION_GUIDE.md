# Figma Implementation Guide
## Screen D: Employee Exit Journey

---

## Quick Start: Leveraging Existing Components

Based on the existing pensions screen (node-id=8017:13192), you already have these components ready to use:

### ✅ Components You Can Reuse Directly

1. **Header Component**
   - Already has: Old Mutual logo, Yu co-brand, hamburger menu, notification bell, YuCoin counter
   - Location: Use the exact header from the pensions screen
   - **Action**: Copy and paste header frame

2. **Hero Section Structure**
   - Color: Change from `#76B657` (green) to `#429479` (teal) for transition moment
   - **Action**: Duplicate hero frame, swap background color, update title text

3. **Description Card Below Hero**
   - Same styling as existing "Daily YuCoin rewards..." card
   - **Action**: Copy card, update text content

4. **Card Container Styles**
   - Border: `1px solid #E3E3E1`
   - Radius: `16px` for primary cards, `8px` for nested cards
   - **Action**: Use existing card auto-layout frames

5. **Typography Styles**
   - All text styles are already defined in the existing screen
   - **Action**: Apply same text styles (Heading 2, Body 1, Label 1, etc.)

---

## 🆕 New Components to Create

### 1. Info Box Component (Green Alert)

**Frame Setup**:
```
Frame: info-box
├─ Auto Layout: Horizontal
├─ Padding: 20px
├─ Gap: 16px
├─ Fill: #ECF9EE
├─ Stroke: 1px #76B657
├─ Corner Radius: 16px
```

**Children**:
- **Icon Frame**: 32px circle, fill `#76B657`, text "i" in white
- **Content Frame**: Auto-layout vertical, gap 8px
  - Title: Label 1 / Bold
  - Body: Label 1 / Regular

**Figma Layers**:
```
info-box
├─ icon-circle (32×32, #76B657)
│  └─ text-i (white)
└─ content
   ├─ title-text
   └─ body-text
```

---

### 2. Protected Item Row Component

**Frame Setup**:
```
Frame: protected-item
├─ Auto Layout: Horizontal
├─ Padding: 12px
├─ Gap: 12px
├─ Fill: #FAFAFE
├─ Corner Radius: 8px
```

**Children**:
- **Icon Square**: 40×40px, radius 8px, fill `#76B657`
  - Add emoji as text layer: 💰 🛡️ 💚
- **Content Frame**: Auto-layout vertical, gap 4px
  - Label: Label 3 / Regular, `#A0A09B`, uppercase
  - Value: Label 1 / Bold, `#1A1A1A`

**Figma Layers**:
```
protected-item
├─ icon-square (40×40, rounded 8px)
│  └─ emoji-text
└─ content
   ├─ label-text (UPPERCASE)
   └─ value-text (Bold)
```

**Create 3 instances**:
1. Pension: 💰 icon, "YOUR PENSION", "R75 193,54"
2. Life: 🛡️ icon, "LIFE COVER", "R850,000"
3. Disability: 💚 icon, "DISABILITY COVER", "R425,000"

---

### 3. Choice Card Component (CRITICAL)

This is the most important new component. Create it as a **Component with Variants**.

**Base Frame Setup**:
```
Frame: choice-card
├─ Auto Layout: Vertical
├─ Padding: 20px
├─ Gap: 12px
├─ Stroke: 2px
├─ Corner Radius: 16px
└─ Width: 328px
```

**Variants** (Create 3):

#### Variant 1: Recommended
```
Properties:
├─ Type: Recommended
├─ Stroke: #76B657
├─ Fill: Linear gradient
   ├─ Start: #ECF9EE (top-left)
   └─ End: #FFFFFF (bottom-right)
   └─ Angle: 135°
```

**Layers**:
```
choice-card/recommended
├─ radio-circle (top-right, 24px)
│  ├─ Fill: #76B657
│  └─ checkmark-icon (white)
├─ recommended-badge
│  ├─ "✓ RECOMMENDED"
│  ├─ Fill: #76B657
│  └─ Text: white, 10px bold
├─ header-row
│  ├─ icon-square (48×48, #76B657, 🏠)
│  └─ text-content
│     ├─ title: "Stay with Old Mutual"
│     └─ subtitle: "Member-for-Life protection"
├─ benefits-list (Auto-layout vertical, gap 8px)
│  ├─ benefit-row × 4
│  │  ├─ check-icon (20px green circle, white ✓)
│  │  └─ benefit-text
└─ member-badge
   ├─ "❤️ MEMBER-FOR-LIFE"
   ├─ Fill: Linear gradient (#E30D76 → #C90B64)
   └─ Text: white, 10px bold
```

#### Variant 2: Warning
```
Properties:
├─ Type: Warning
├─ Stroke: #FFD600
└─ Fill: #FFFFFF
```

**Layers**:
```
choice-card/warning
├─ radio-circle (empty, stroke only)
├─ header-row
│  ├─ icon-square (48×48, #FFD600, 💸)
│  └─ text-content
├─ consequences-list
│  ├─ consequence-row × 3
│  │  ├─ x-icon (20px gray circle, ✗)
│  │  └─ consequence-text
└─ warning-box
   ├─ Fill: rgba(255,214,0,0.1)
   ├─ Stroke: #FFD600
   └─ text: "⚠️ Most people who cash out..."
```

#### Variant 3: Neutral
```
Properties:
├─ Type: Neutral
├─ Stroke: #E3E3E1
└─ Fill: #FFFFFF
```

**Layers**:
```
choice-card/neutral
├─ radio-circle (empty)
├─ header-row
│  ├─ icon-square (48×48, #E3E3E1, 📤)
│  └─ text-content
└─ mixed-list
   ├─ item-row × 4 (1 check, 3 x icons)
```

---

### 4. Benefit/Consequence Row Component

**Frame Setup**:
```
Frame: list-item-row
├─ Auto Layout: Horizontal
├─ Gap: 8px
├─ Height: hug
```

**Variants** (Create 2):

#### Variant 1: Positive (Check)
```
list-item-row/positive
├─ icon (20px circle, #76B657, white ✓)
└─ text (Label 1 / Regular, #464647)
```

#### Variant 2: Negative (X)
```
list-item-row/negative
├─ icon (20px circle, #E3E3E1, gray ✗)
└─ text (Label 1 / Regular, #464647)
```

---

### 5. Support Section Component

**Frame Setup**:
```
Frame: support-section
├─ Auto Layout: Horizontal
├─ Padding: 20px
├─ Gap: 16px
├─ Fill: #FAFAFE
├─ Stroke: 1px #E3E3E1
├─ Corner Radius: 16px
```

**Layers**:
```
support-section
├─ icon-circle (48px)
│  ├─ Fill: white
│  ├─ Stroke: 2px #E3E3E1
│  └─ emoji: 👤
└─ content
   ├─ title: "Need help deciding?"
   └─ text: "Your adviser is here..."
```

---

## Step-by-Step Figma Workflow

### Phase 1: Setup (10 min)
1. ✅ Open existing Old Mutual Concepts file
2. ✅ Duplicate the pensions screen frame
3. ✅ Rename to "Screen D - Employee Exit"
4. ✅ Copy header component (no changes needed)

### Phase 2: Hero Section (15 min)
5. ✅ Duplicate hero from pensions screen
6. ✅ Change background color: `#76B657` → `#429479`
7. ✅ Update title text: "Your pension contributions" → "You're leaving your employer"
8. ✅ Remove "Refer this product" button
9. ✅ Update description card text

### Phase 3: Info Box (10 min)
10. ✅ Create new frame for info box
11. ✅ Add icon circle component
12. ✅ Add title and body text
13. ✅ Apply green background and border

### Phase 4: Protected Items Section (20 min)
14. ✅ Create "What you've built so far" card container
15. ✅ Create protected-item component
16. ✅ Duplicate 3 times (pension, life, disability)
17. ✅ Update emoji icons and values

### Phase 5: Choice Cards (45 min - MOST IMPORTANT)
18. ✅ Create base choice-card frame
19. ✅ Add all internal components (header, list items, etc.)
20. ✅ Create component with 3 variants
21. ✅ Style variant 1 (recommended): green border, gradient, badge
22. ✅ Style variant 2 (warning): yellow border, warning box
23. ✅ Style variant 3 (neutral): gray border, mixed list
24. ✅ Test all variants with real content

### Phase 6: Support & CTA (15 min)
25. ✅ Create support section component
26. ✅ Copy CTA button from existing screen
27. ✅ Update button text: "Continue with Old Mutual"
28. ✅ Adjust button shadow (same as existing)

### Phase 7: Polish & Test (20 min)
29. ✅ Check spacing consistency (use 8px grid)
30. ✅ Verify all colors match design system
31. ✅ Test with different text lengths
32. ✅ Add hover states to interactive elements
33. ✅ Create prototype connections (optional)
34. ✅ Export preview image

---

## Color Swatches to Add

If not already in your Figma file, add these color styles:

```
Old Mutual / Primary Dark: #1A1A1A
Old Mutual / Primary Teal: #429479
Old Mutual / Secondary Green: #76B657
Old Mutual / Warning Yellow: #FFD600
Old Mutual / Success Light: #ECF9EE
Yu / Brand Pink: #E30D76
Neutral / Background: #FAFAFE
Neutral / Border: #E3E3E1
Ink / Subtle: #A0A09B
Ink / Strong: #464647
Ink / White: #FFFFFF
```

---

## Text Styles Checklist

Verify these are applied:

- ✅ Heading 2 (28px Bold) → Hero title
- ✅ Body 1 / Bold (20px Bold) → Section titles
- ✅ Label 1 / Bold (16px Bold) → Card titles, descriptions
- ✅ Label 1 / Regular (14px Regular) → Body text
- ✅ Label 2 / Bold (12px Bold) → List items
- ✅ Label 3 / Regular (10px Regular) → Labels, badges

---

## Auto-Layout Settings

### Main Screen Frame
```
Direction: Vertical
Gap: 32px
Padding: 0 0 40px 0
Fill: #FFFFFF
```

### Content Section
```
Direction: Vertical
Gap: 24px
Padding: 0 24px
```

### Choice Cards Container
```
Direction: Vertical
Gap: 16px
```

### Individual Card
```
Direction: Vertical
Gap: 12px
Padding: 20px
```

---

## Constraints & Responsiveness

Set these constraints for mobile-first design:

| Element | Left | Right | Top | Bottom |
|---------|------|-------|-----|--------|
| Header | Fixed | Fixed | Fixed | - |
| Content | Fixed | Fixed | - | - |
| Cards | Scale | Scale | - | - |
| CTA Button | Fixed | Fixed | - | Fixed |

---

## Export Settings

For presentation deck:

```
Format: PNG
Scale: 2x
Background: Include
Name: screen-d-employee-exit@2x.png
```

For development handoff:

```
Format: SVG (icons)
Format: PNG 1x, 2x, 3x (raster elements)
Include: All assets used
```

---

## Component Library Structure

After creating all components, organize like this:

```
📁 Components
├─ 📁 Old Mutual - Existing
│  ├─ Header
│  ├─ Hero Section
│  ├─ Card Container
│  └─ Button / CTA
└─ 📁 Old Mutual - New (Screen D)
   ├─ Info Box
   ├─ Protected Item Row
   ├─ Choice Card (3 variants)
   ├─ List Item Row (2 variants)
   └─ Support Section
```

---

## Interactive Prototype (Optional)

If creating a clickable prototype:

1. **Choice Card Interaction**:
   - Click → Radio button fills
   - Click → Card border highlights
   - Click → CTA button becomes active

2. **CTA Button**:
   - Click → Navigate to confirmation screen (or next step)

3. **Support Section**:
   - Click → Open adviser contact overlay (or navigate)

4. **Hover States**:
   - Cards: Add subtle shadow
   - Button: Lift effect
   - Info box: None (static)

---

## Testing Checklist

Before finalizing:

- [ ] View at 100% zoom (actual mobile size)
- [ ] Test with longest possible text strings
- [ ] Test with shortest text strings
- [ ] Check all spacing is 8px grid-aligned
- [ ] Verify all colors are from style library
- [ ] Verify all text uses defined styles
- [ ] Check that radio circles align properly
- [ ] Ensure touch targets are 44px minimum
- [ ] Review against existing pensions screen for consistency
- [ ] Get feedback from team on choice card copy
- [ ] Confirm emoji rendering across platforms

---

## Common Pitfalls to Avoid

❌ **Don't**:
1. Make choice cards different widths
2. Use arbitrary spacing (stick to 8px grid)
3. Create text without styles (always use text styles)
4. Forget to make components (you'll need variants)
5. Use raster images for icons (use vectors or emoji)
6. Make radio buttons smaller than 24px
7. Forget hover states for interactive elements
8. Use lorem ipsum (use real copy from spec)

✅ **Do**:
1. Reuse existing components wherever possible
2. Create variants for choice cards (saves time)
3. Use auto-layout for all containers
4. Name layers clearly ("choice-card/recommended")
5. Group related elements into frames
6. Test with real SA Rand amounts (R formatting)
7. Keep file organized with pages/sections
8. Document component usage in Figma notes

---

## Design Handoff Notes

When sharing with developers:

1. **Share Figma Link** with "Can view" access
2. **Enable Dev Mode** for accurate specs
3. **Export Assets**: All icons, logos, illustrations
4. **Document Interactions**: Which elements are clickable?
5. **Note Dynamic Content**: Which text/values come from API?
6. **Specify States**: Default, hover, active, selected, disabled
7. **Include Edge Cases**: What if no adviser? What if amounts are $0?

---

## Time Estimate

| Phase | Time | Difficulty |
|-------|------|------------|
| Setup & Hero | 25 min | Easy |
| Info Box | 10 min | Easy |
| Protected Items | 20 min | Easy |
| **Choice Cards** | **45 min** | **Hard** |
| Support & CTA | 15 min | Easy |
| Polish & Test | 20 min | Medium |
| **Total** | **~2 hours** | **Medium** |

**Note**: Choice cards are the hardest part because they require variants, complex layouts, and precise styling. Take your time here—this is the CRITICAL component.

---

## Resources

- **Existing Screen Reference**: node-id=8017:13192
- **Design Spec**: SCREEN_D_DESIGN_SPEC.md
- **HTML Preview**: screen-d-employee-exit.html
- **Brand Guidelines**: Project_Knowledge/Internal_Brief

---

## Next Steps After Figma

1. ✅ Share with team for feedback
2. ✅ Test with Old Mutual stakeholders
3. ✅ Iterate based on feedback
4. ✅ Create remaining 7 screens using same components
5. ✅ Build 8-slide presentation deck
6. ✅ Prepare for SA meetings (Feb 9-16)

---

*Guide created: February 3, 2026*  
*For: Screen D - Employee Exit Journey*  
*Project: Old Mutual ❤️ Yu*  
*Estimated completion time: 2 hours for experienced Figma user*

**🎯 Focus Areas**: Choice cards (45 min) → Protected items (20 min) → Everything else (55 min)
