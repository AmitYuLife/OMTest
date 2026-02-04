# Screen D: Employee Exit Journey - Design Specification
## Old Mutual ❤️ Yu Unified Engagement Layer

---

## Overview

**Screen Purpose**: The CRITICAL screen that preserves member value at the highest economic leverage point—job change/exit.

**Design Priority**: This is the single most important screen in the 8-screen concept deck. It must be crystal clear, empathetic, and make preservation the obvious choice.

---

## Design Principles Applied

1. **Empathy First**: Acknowledge the transition moment without creating anxiety
2. **Clear Choice Architecture**: Three paths with transparent consequences
3. **Behavioral Nudges**: Make the right choice the easy choice (without pressure)
4. **Value Visibility**: Show what they've built and what they could keep or lose
5. **Continuity Emphasis**: "Member-for-Life" positioning

---

## Visual Hierarchy

### 1. Hero Section
**Color**: Old Mutual Primary Teal (`#429479`)
**Purpose**: Set the emotional tone with empathy

**Elements**:
- **Old Mutual Logo** (white, small)
- **Hero Title**: "You're leaving your employer"
  - Font: Bariol Bold
  - Size: 28px
  - Line Height: 32px
  - Letter Spacing: 1px
  - Color: White

**Design Note**: The teal (rather than green) signals a transition moment—calmer, more contemplative than the optimistic green.

---

### 2. Description Card
**Background**: `#FAFAFE` (Neutral/5)
**Border**: 1px solid `#E3E3E1` (Neutral/30)
**Radius**: 0 0 16px 16px (continues from hero)

**Copy**: "Your benefits don't have to leave you. Keep your pension and protection with Old Mutual."

**Design Note**: This overlaps the hero by 8px (margin-top: -8px) to create visual continuity—same pattern as the existing pensions screen.

---

### 3. Info Box (Contextual Nudge)
**Background**: `#ECF9EE` (Success/10)
**Border**: 1px solid `#76B657` (OM Secondary)
**Radius**: 16px
**Padding**: 20px

**Layout**:
- Icon (left): 32px circle, `#76B657` background, white "i"
- Content (right):
  - **Title**: "What happens next?" (Bold, 16px)
  - **Body**: "You have options for your pension and risk cover. Take your time to choose what works best for you." (Regular, 14px)

**Design Note**: Green (success color) signals hope and positive action, not fear.

---

### 4. What You've Built (Value Summary)
**Container**: White card with `#E3E3E1` border, 16px radius
**Padding**: 20px

**Title**: "What you've built so far" (Bold, 16px)

**Items** (3 rows):
Each item has:
- **Icon**: 40px square with 8px radius, `#76B657` background
  - Pension: 💰 emoji
  - Life Cover: 🛡️ emoji
  - Disability Cover: 💚 emoji
- **Label**: Uppercase, 12px, `#A0A09B` (Ink/Subtle)
- **Value**: Bold, 16px, `#1A1A1A` (OM Dark)

**Sample Data**:
- Your Pension: R75 193,54
- Life Cover: R850,000
- Disability Cover: R425,000

**Design Note**: This reinforces what they stand to preserve or lose. The emoji icons keep it friendly and human.

---

### 5. Choice Cards (The Critical Decision)

#### General Structure
- **Spacing**: 16px gap between cards
- **Padding**: 20px inside each card
- **Radius**: 16px
- **Radio Button**: Top-right corner (24px circle)

---

#### Option 1: Stay with Old Mutual (RECOMMENDED)

**Visual Treatment**:
- **Border**: 2px solid `#76B657`
- **Background**: Linear gradient from `#ECF9EE` to `#FFFFFF` (135deg)
- **Badge**: "✓ RECOMMENDED" in white on `#76B657`, 6px padding, 12px radius

**Layout**:
- **Icon**: 48px square, 12px radius, `#76B657` background, 🏠 emoji (24px)
- **Title**: "Stay with Old Mutual" (Bold, 18px)
- **Subtitle**: "Member-for-Life protection" (Regular, 12px, `#A0A09B`)

**Benefits List** (4 items with green check icons):
- Keep your full pension value
- Continue your life & disability cover
- Your adviser stays with you
- No paperwork, seamless transition

**Member Badge**: 
- Background: Linear gradient `#E30D76` to `#C90B64`
- Text: "❤️ MEMBER-FOR-LIFE" (white, 10px bold)
- Position: Bottom of card, 16px margin-top

**Radio State**: Filled circle with white checkmark

---

#### Option 2: Cash Out (WARNING)

**Visual Treatment**:
- **Border**: 2px solid `#FFD600` (warning color)
- **Background**: White
- **No Badge**: Absence of positive badge is intentional

**Layout**:
- **Icon**: 48px square, 12px radius, `#FFD600` background, 💸 emoji
- **Title**: "Cash out" (Bold, 18px)
- **Subtitle**: "Take your money now" (Regular, 12px, `#A0A09B`)

**Consequences List** (3 items with gray X icons):
- Up to 36% lost to tax
- Lose your life & disability cover
- Retirement savings reduced

**Warning Box**:
- Background: `rgba(255, 214, 0, 0.1)` (10% yellow)
- Border: 1px solid `#FFD600`
- Radius: 8px
- Padding: 12px
- **Text**: "⚠️ Most people who cash out wish they hadn't. R75k today could be worth R450k+ at retirement." (Bold, 12px, `#464647`)

**Design Note**: Uses social proof ("most people") and concrete long-term impact to gently discourage without fear-mongering.

---

#### Option 3: Transfer to Another Fund (NEUTRAL)

**Visual Treatment**:
- **Border**: 2px solid `#E3E3E1` (neutral gray)
- **Background**: White
- **No Badge**: Neutral option

**Layout**:
- **Icon**: 48px square, 12px radius, `#E3E3E1` background, 📤 emoji
- **Title**: "Transfer to another fund" (Bold, 18px)
- **Subtitle**: "Move to a different provider" (Regular, 12px)

**Mixed Consequences** (1 green check, 3 gray X):
- ✓ Keep your pension value
- ✗ Lose your current life & disability cover
- ✗ May require new medical underwriting
- ✗ Additional paperwork required

**Design Note**: Honest and balanced. Shows it's not terrible, but also not optimal.

---

### 6. Support Section
**Background**: `#FAFAFE`
**Border**: 1px solid `#E3E3E1`
**Radius**: 16px
**Padding**: 20px

**Layout**:
- **Icon**: 48px circle, white background, 2px `#E3E3E1` border, 👤 emoji
- **Title**: "Need help deciding?" (Bold, 14px)
- **Text**: "Your adviser is here to guide you through your options at no extra cost." (Regular, 12px, `#A0A09B`)

**Design Note**: Emphasizes that advisers are partners, not obstacles. "No extra cost" removes friction.

---

### 7. Primary CTA Button
**Background**: `#76B657` (OM Secondary)
**Text**: "Continue with Old Mutual" (Bold, 16px, white)
**Padding**: 16px 24px
**Radius**: 16px
**Shadow**: 0px 4px 0px `rgba(66, 148, 121, 0.3)`
**Width**: 100%

**Hover State**:
- Background: `#5BA348` (darker green)
- Transform: translateY(-2px)
- Shadow: 0px 6px 0px

**Active State**:
- Transform: translateY(2px)
- Shadow: 0px 2px 0px

**Design Note**: The button copy reinforces the recommended choice. If they want other options, they use the radio buttons.

---

## Color Palette Reference

| Element | Color Name | Hex | Usage |
|---------|------------|-----|--------|
| Primary Dark | OM Dark | `#1A1A1A` | Body text, titles |
| Primary Green | OM Secondary | `#76B657` | Recommended choice, CTAs |
| Primary Teal | OM Primary | `#429479` | Hero background |
| Subtle Text | Ink/Subtle | `#A0A09B` | Labels, secondary text |
| Body Text | Ink/Strong | `#464647` | Body copy |
| Background | Neutral/5 | `#FAFAFE` | Card backgrounds |
| Border | Neutral/30 | `#E3E3E1` | Borders, dividers |
| Warning Yellow | Vibrant/Yellow | `#FFD600` | Warning states |
| Success Green | Status/Success/10 | `#ECF9EE` | Info box background |
| Yu Brand | Primary/100 | `#E30D76` | Member badge |
| White | Ink/White | `#FFFFFF` | Backgrounds, text on dark |

---

## Typography Reference

| Element | Font | Size | Weight | Line Height | Letter Spacing |
|---------|------|------|--------|-------------|----------------|
| Hero Title | Bariol | 28px | 700 | 32px | 1px |
| Choice Title | Bariol | 18px | 700 | 24px | 0px |
| Section Title | Bariol | 20px | 700 | 24px | 0.8px |
| Card Title | Bariol | 16px | 700 | 24px | 0.6px |
| Body Text | Bariol | 14px | 400 | 20px | 0.4px |
| Label | Bariol | 12px | 400 | 16px | 0.4px |
| Label Bold | Bariol | 12px | 700 | 16px | 0.4px |
| Badge | Bariol | 10px | 700 | 12px | 0.4px |

---

## Spacing System

**Container Padding**: 24px (left/right)
**Section Gaps**: 24px (between major sections)
**Card Gaps**: 16px (between cards)
**Element Gaps**: 12px (within cards)
**Tight Gaps**: 8px (icon to text)
**Micro Gaps**: 4px (badge to title)

---

## Icon System

### Choice Card Icons (48px)
- **Recommended**: 🏠 (Home - stability, staying)
- **Cash Out**: 💸 (Money flying away - loss)
- **Transfer**: 📤 (Outbox - moving elsewhere)

### Protected Items Icons (40px)
- **Pension**: 💰 (Money bag - accumulated wealth)
- **Life Cover**: 🛡️ (Shield - protection)
- **Disability Cover**: 💚 (Green heart - health protection)

### Supporting Icons
- **Info**: White "i" on green circle (32px)
- **Adviser**: 👤 emoji (24px)
- **Check**: White ✓ on green circle (20px)
- **X**: Gray ✗ on gray circle (20px)

**Design Note**: Emoji-based icons keep the design approachable and human. Can be replaced with custom SVG icons if brand requires.

---

## Behavioral Design Elements

### 1. **Default/Recommended Pattern**
- Green highlighting makes Option 1 visually dominant
- Pre-selected radio state suggests this is the path most choose
- Badge reinforces social proof

### 2. **Gentle Consequences**
- Option 2 uses ⚠️ emoji, not ❌ or 🚫 (less harsh)
- Warning text uses social proof ("most people") not fear ("you'll regret this")
- Shows long-term impact with concrete numbers (R75k → R450k+)

### 3. **Continuity Cues**
- "Member-for-Life" badge uses Yu heart (❤️) + brand gradient
- Support section emphasizes "Your adviser stays with you"
- "Seamless transition" and "No paperwork" reduce friction perception

### 4. **Transparency**
- All three options clearly visible (no hiding of alternatives)
- Honest pros/cons for each path
- Neutral option (Transfer) treated fairly, not demonized

---

## Responsive Considerations

**Mobile First (375px)**:
- Current design is optimized for 375px viewport
- All touch targets meet 44px minimum (buttons, radio circles)
- Font sizes are mobile-legible
- No horizontal scrolling

**Tablet/Desktop** (if needed):
- Center container with max-width: 375px
- Add side margins: auto
- Keep mobile layout (no multi-column)

---

## Accessibility Notes

1. **Color Contrast**:
   - All text meets WCAG AA standards
   - Green on white: 4.5:1+
   - Dark text on light backgrounds: 7:1+

2. **Touch Targets**:
   - Radio circles: 24px (expandable to 44px click area)
   - Buttons: 48px minimum height
   - Cards: Entire card is clickable

3. **Screen Reader**:
   - Clear hierarchy with semantic HTML (h1, h2, h3)
   - Alt text for all icons
   - Radio buttons properly labeled

4. **Cognitive Load**:
   - Only 3 choices (not overwhelming)
   - Visual hierarchy guides eye down the page
   - Most important info (what they've built) shown before choices

---

## Key Messaging

### Do Say:
✅ "Your benefits don't have to leave you"
✅ "What you've built so far"
✅ "Member-for-Life protection"
✅ "Your adviser stays with you"
✅ "Take your time to choose"
✅ "Seamless transition"

### Don't Say:
❌ "Don't leave us!"
❌ "Other options are bad"
❌ "You'll lose everything if you cash out"
❌ "Quick! Decide now!"
❌ "Fees apply"
❌ "Complex terms and conditions"

---

## Interaction States

### Choice Cards
**Default**: 2px border, white/gradient background
**Hover**: Add shadow `0 4px 12px rgba(0,0,0,0.08)`
**Selected**: Fill radio circle, highlight border (green for Option 1)
**Focus**: Add blue outline ring for keyboard navigation

### CTA Button
**Default**: Green background, 4px shadow
**Hover**: Darker green, lift up 2px, deeper shadow
**Active**: Push down 2px, shallower shadow
**Disabled**: Gray background, 50% opacity, no shadow

---

## Animation Recommendations

1. **Page Entry**:
   - Hero slides in from top (200ms ease-out)
   - Cards fade in sequentially (100ms stagger)

2. **Choice Selection**:
   - Radio circle fills with scale animation (150ms ease-out)
   - Card border color transition (200ms ease)

3. **CTA Hover**:
   - Transform and shadow change (200ms ease-out)

4. **Micro-interactions**:
   - Info icon pulse on page load (subtle, 1 second delay)
   - Member badge gentle glow animation (optional)

---

## Data Integration Points

### Dynamic Values
1. **Pension Balance**: R75 193,54 → API: `member.pension.total_value`
2. **Life Cover**: R850,000 → API: `member.risk.life_cover_amount`
3. **Disability Cover**: R425,000 → API: `member.risk.disability_cover_amount`
4. **Tax Calculation**: "Up to 36%" → API: `calculate_tax(member.pension.total_value, 'withdrawal')`
5. **Retirement Projection**: "R450k+" → API: `project_retirement_value(member.pension.total_value, member.age, retirement_age=65)`
6. **Adviser Info**: "Your adviser" → API: `member.adviser.display_name`

### Personalization Hooks
- If no adviser assigned: Hide support section OR change copy to "We can assign you an adviser"
- If high net worth: Adjust retirement projection upward
- If young member (<30): Emphasize longer compound growth in warning text
- If near retirement (>55): Adjust messaging to focus on immediate income needs

---

## Figma Implementation Checklist

- [ ] Create component for choice card (3 variants: recommended, warning, neutral)
- [ ] Create component for protected item row
- [ ] Create component for benefit check/cross icons
- [ ] Set up auto-layout for vertical stacking
- [ ] Configure responsive constraints
- [ ] Add component states (default, hover, selected)
- [ ] Create color styles from palette
- [ ] Create text styles from typography scale
- [ ] Add spacing tokens (8px grid system)
- [ ] Test with real data (long names, different amounts)
- [ ] Prototype radio button interactions
- [ ] Prototype CTA button states
- [ ] Export assets at 1x, 2x, 3x for iOS/Android

---

## Success Metrics (Post-Launch)

If this screen performs well, we'd expect:
- **Preservation rate**: 70%+ choose Option 1
- **Cash-out rate**: <15% choose Option 2
- **Transfer rate**: ~15% choose Option 3
- **Time on screen**: 60-120 seconds (enough time to read and decide)
- **Adviser contact rate**: 10-15% click support section
- **Completion rate**: 85%+ proceed to next step (not abandon)

---

## Design Rationale Summary

This screen is designed to:

1. **Acknowledge the Transition**: Job change is emotional—we meet them with empathy
2. **Make the Right Choice Easy**: Green highlighting + benefits list make Option 1 obvious
3. **Be Transparent**: Show all options honestly, including consequences
4. **Reduce Friction**: "No paperwork," "seamless," "adviser stays with you"
5. **Preserve Value**: Show what they've built before asking them to choose
6. **Support, Don't Pressure**: "Take your time," adviser available, no urgency tactics

**This screen embodies the project's core principle: Member-first engagement that improves outcomes through behavioral intelligence, not sales pressure.**

---

## Next Steps for Design Execution

1. **Create in Figma** using existing Old Mutual components (see reference file)
2. **Replace emoji icons** with Old Mutual brand iconography (if available)
3. **Use real member data** for testing (with privacy considerations)
4. **Test with SA users** for cultural/linguistic appropriateness
5. **A/B test copy** variations (especially warning text)
6. **Integrate with other screens** (what comes before? what comes after?)
7. **Design error states** (what if API fails? what if no data?)
8. **Design confirmation screen** (after they select an option)

---

*Document created: February 3, 2026*  
*Screen: D - Employee Exit Journey*  
*Designer: Amit*  
*Project: Old Mutual ❤️ Yu Unified Engagement Layer*
