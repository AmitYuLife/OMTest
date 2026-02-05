# Screen A: Unified Member Home - Design Specification
## 10X ❤️ Yu Unified Engagement Layer

---

## Overview

**Screen Purpose**: The ANCHOR SCREEN—the foundational experience that shows retirement + risk as one unified financial home.

**Design Priority**: This is the member's "home base" where they return daily. Must feel personal, clear, and empowering—never overwhelming.

---

## Design Principles Applied

1. **Unified Value View**: Retirement and risk shown together as natural partners
2. **Personal Dashboard**: Feels like "my financial home," not a product list
3. **Clear Language**: "Your future income" + "Your family protection" (not jargon)
4. **Behavioral Nudges**: Gentle, helpful suggestions (not sales pressure)
5. **Optional Actions**: Everything is optional, nothing forced

---

## Visual Hierarchy

### 1. Header Component
**Height**: 92px
**Purpose**: Brand presence + navigation + rewards

**Elements**:
- **Left**: Hamburger menu (24px) + Notification bell (24px)
- **Center**: 10X logo + ❤️ separator + Yu square
- **Right**: YuCoin count (2,502) + coin icon (24px)

**Colors**:
- Background: `#FFFFFF`
- Shadow: 0px 4px 24px rgba(0,0,0,0.08)
- Border radius: 0 0 40px 40px

---

### 2. Hero Section
**Height**: 300px
**Purpose**: Welcome + set emotional tone + show unified value

**Layout**:
```
┌───────────────────────────────────────┐
│                          [decoration] │
│  Good morning, Sarah                  │
│  Your financial home                  │
│  Your retirement and protection...    │
└───────────────────────────────────────┘
```

**Elements**:
- **Greeting**: "Good morning, [Name]"
  - Font: Bariol Regular, 16px
  - Color: White, 90% opacity
  - Personalized by time of day

- **Hero Title**: "Your financial home"
  - Font: Bariol Bold, 28px
  - Line height: 32px
  - Letter spacing: 1px
  - Color: White

- **Subtitle**: "Your retirement and protection working together for your future"
  - Font: Bariol Regular, 14px
  - Line height: 20px
  - Color: White, 90% opacity
  - Max width: 250px

**Colors**:
- Background: `#3FAACF` (10X Teal)
- Text: `#FFFFFF`
- Illustration: White circles, 20-40% opacity

**Design Note**: Green (not teal) signals optimism and growth—appropriate for daily home screen.

---

### 3. Quick Stats Bar
**Position**: Overlaps hero by 8px (margin-top: -8px)
**Purpose**: At-a-glance unified value summary

**Layout**:
```
┌──────────────────────────────────────────────────┐
│  +12.3%      R1,025k      ✓ Protected           │
│  This year   Total value   Family cover         │
└──────────────────────────────────────────────────┘
```

**Elements**: 3 equal-width stat items

**Stat 1: Growth**
- Value: "+12.3%" (Bold, 20px, `#76B657`)
- Label: "THIS YEAR" (Regular, 10px, `#A0A09B`, uppercase)

**Stat 2: Total Value**
- Value: "R1,025k" (Bold, 20px, `#76B657`)
- Label: "TOTAL VALUE" (Regular, 10px, `#A0A09B`, uppercase)

**Stat 3: Protection Status**
- Value: "✓ Protected" (Bold, 20px, `#76B657`)
- Label: "FAMILY COVER" (Regular, 10px, `#A0A09B`, uppercase)

**Container**:
- Background: `#FFFFFF`
- Border: 1px solid `#E3E3E1`
- Radius: 0 0 16px 16px (continues from hero)
- Padding: 20px 24px

**Design Note**: Shows combined value immediately—user sees "one financial picture" not separate products.

---

### 4. Nudge Banner (Behavioral Intelligence)
**Purpose**: Gentle, personalized suggestion without pressure

**Layout**:
```
┌────────────────────────────────────────────────┐
│  ✨  One small change could improve your      │
│      future                                    │
│      See what you could do →                   │
└────────────────────────────────────────────────┘
```

**Elements**:
- **Icon**: 32px circle, `#76B657` background, ✨ emoji (18px)
- **Text**: "One small change could improve your future"
  - Bold, 14px, `#1A1A1A`
- **CTA**: "See what you could do →"
  - Bold, 12px, `#76B657`, underlined

**Container**:
- Background: `#ECF9EE` (Success/10)
- Border: 1px solid `#76B657`
- Radius: 16px
- Padding: 16px
- Gap: 12px (icon to content)

**Behavioral Note**: 
- Always positive framing ("improve" not "fix")
- Curiosity-driven ("See what" not "You must")
- Optional (underlined link, not button)

**Dynamic Examples**:
- "One small change could improve your future"
- "You're on track—here's how to stay there"
- "Great growth this month! Keep it up"

---

### 5. Value Cards Section: Retirement + Protection

**Section Header**:
- Title: "Your benefits" (Bold, 20px, letter-spacing 0.8px)
- Action: "View all" (Bold, 14px, `#76B657`, link)

---

#### Card 1: Retirement (Your Future Income)

**Structure**:
```
┌────────────────────────────────────────────────┐
│  💰  RETIREMENT               →               │
│      Your future income                        │
│                                                │
│  R75,193                                       │
│  ↑ +R324 this month                           │
│                                                │
│  Building towards R450k+ at retirement        │
│                                                │
│  [View details] [Increase contribution]       │
└────────────────────────────────────────────────┘
```

**Header**:
- **Icon**: 48×48px square, 12px radius
  - Background: Linear gradient `#76B657` → `#5BA348`
  - Emoji: 💰 (24px)
- **Category**: "YOUR FUTURE INCOME" (10px, `#A0A09B`, uppercase)
- **Title**: "Retirement" (18px Bold, `#1A1A1A`)
- **Arrow**: 24px chevron, `#A0A09B` (clickable to details)

**Value Display**:
- **Amount**: "R75,193" (32px Bold, `#1A1A1A`)
- **Growth**: "↑ +R324 this month" (12px Bold, `#76B657` with up arrow)

**Context**:
- **Subtitle**: "Building towards R450k+ at retirement"
  - 12px Regular, `#A0A09B`
  - Shows future projection (AI-calculated based on age, contributions)

**Actions**: 2 buttons, equal width
- Button 1: "View details" (navigates to full pension screen)
- Button 2: "Increase contribution" (modal or flow)
- Style: White background, `#E3E3E1` border, 8px radius
- Hover: Border → `#76B657`, text → `#76B657`

**Container**:
- Background: `#FFFFFF`
- Border: 1px solid `#E3E3E1`
- Radius: 16px
- Padding: 20px
- Hover: Shadow 0 4px 12px rgba(0,0,0,0.08)

---

#### Card 2: Protection (Your Family Protection)

**Structure**:
```
┌────────────────────────────────────────────────┐
│  🛡️  RISK COVER              →                │
│      Your family protection                    │
│                                                │
│  ┌──────────────────────────────────────────┐ │
│  │  💼  Life cover           R850k         │ │
│  └──────────────────────────────────────────┘ │
│  ┌──────────────────────────────────────────┐ │
│  │  💚  Disability cover     R425k         │ │
│  └──────────────────────────────────────────┘ │
│  ┌──────────────────────────────────────────┐ │
│  │  🏠  Funeral cover        R50k          │ │
│  └──────────────────────────────────────────┘ │
│                                                │
│  You're well protected—here's why →           │
│                                                │
│  [View details] [Adjust cover]                │
└────────────────────────────────────────────────┘
```

**Header**: Same structure as Retirement card
- **Icon**: Gradient `#429479` → `#357A61` (teal)
- **Category**: "YOUR FAMILY PROTECTION"
- **Title**: "Risk cover"

**Protection Breakdown**: 3 items
Each item:
- Background: `#FAFAFE`
- Radius: 8px
- Padding: 12px
- Layout: [Icon 20px] [Label] → [Value]

**Item 1: Life**
- Icon: 💼 emoji (20px)
- Label: "Life cover" (14px Regular, `#464647`)
- Value: "R850k" (16px Bold, `#1A1A1A`)

**Item 2: Disability**
- Icon: 💚 emoji (20px)
- Label: "Disability cover" (14px Regular, `#464647`)
- Value: "R425k" (16px Bold, `#1A1A1A`)

**Item 3: Funeral**
- Icon: 🏠 emoji (20px)
- Label: "Funeral cover" (14px Regular, `#464647`)
- Value: "R50k" (16px Bold, `#1A1A1A`)

**Nudge**:
- Text: "You're well protected—here's why →"
- Style: 12px Regular, `#A0A09B`
- Links to protection education/explanation

**Actions**: Same button style as Retirement card
- Button 1: "View details"
- Button 2: "Adjust cover"

**Design Note**: Shows ALL protection in one place—makes the unified value visible.

---

### 6. Optional Actions Grid

**Section Title**: "More ways to grow" (20px Bold)

**Layout**: 2×2 grid, 12px gap

```
┌─────────────────┐  ┌─────────────────┐
│  ➕             │  │  🚗             │
│  Top up         │  │  Add GAP        │
│  protection     │  │  cover          │
└─────────────────┘  └─────────────────┘
┌─────────────────┐  ┌─────────────────┐
│  🌟             │  │  💪             │
│  Coaching       │  │  Wellbeing      │
└─────────────────┘  └─────────────────┘
```

**Tile Structure**:
- **Icon**: 40×40px square, 10px radius, `#FAFAFE` background
- **Title**: 14px Bold, `#1A1A1A`
- **Subtitle**: 12px Regular, `#A0A09B`
- **Container**: White, `#E3E3E1` border, 12px radius, 16px padding
- **Hover**: Border → `#76B657`, shadow

**Tiles**:

1. **Top up protection**
   - Icon: ➕
   - Subtitle: "Add extra cover for life changes"

2. **Add GAP cover**
   - Icon: 🚗
   - Subtitle: "Protect your vehicle investment"

3. **Coaching**
   - Icon: 🌟
   - Subtitle: "Get financial wellness support"

4. **Wellbeing**
   - Icon: 💪
   - Subtitle: "Earn rewards for healthy habits"

**Design Note**: These are **lightly shown**—available but not pushy. Yu cross-sell naturally integrated.

---

### 7. Recent Activity Feed

**Section Header**:
- Title: "Recent activity" (Bold, 20px)
- Action: "View all" (Bold, 14px, `#76B657`)

**Container**:
- Background: `#FAFAFE`
- Border: 1px solid `#E3E3E1`
- Radius: 16px
- Padding: 20px

**Activity Items** (3 shown):

**Item Structure**:
```
┌────────────────────────────────────────────────┐
│  [Icon]  Title                     Value       │
│          Time                                  │
├────────────────────────────────────────────────┤
```

**Item 1: Contribution**
- Icon: 💰 (40×40px square, white bg, 10px radius)
- Title: "Contribution received" (14px Bold, `#1A1A1A`)
- Time: "Today, 09:30" (12px Regular, `#A0A09B`)
- Value: "+R324" (16px Bold, `#76B657`)

**Item 2: YuCoins**
- Icon: 🪙
- Title: "YuCoins earned"
- Time: "Yesterday"
- Value: "+15" (green)

**Item 3: Growth**
- Icon: 📈
- Title: "Investment growth"
- Time: "This week"
- Value: "+R1,245" (green)

**Design Note**: Shows unified activity—pension contributions + rewards + growth all together.

---

### 8. Bottom Navigation

**Height**: 80px (includes safe area)
**Position**: Fixed at bottom
**Background**: `#FFFFFF`
**Border**: 1px solid `#E3E3E1` (top only)
**Shadow**: 0 -2px 8px rgba(0,0,0,0.04)

**Items**: 4 equal-width nav items

**Structure per item**:
- Icon: 24×24px
- Label: 10px Bold, uppercase
- Layout: Vertical (icon above label)
- Padding: 4px 12px
- Gap: 4px

**Items**:

1. **Home** (Active)
   - Icon: House (filled)
   - Color: `#76B657` (active state)

2. **Activity**
   - Icon: Clock
   - Color: `#A0A09B` (inactive)

3. **Insights**
   - Icon: Bar chart
   - Color: `#A0A09B`

4. **Profile**
   - Icon: User
   - Color: `#A0A09B`

**Active State**:
- Icon color: `#76B657`
- Label color: `#76B657`
- Label weight: Bold

**Inactive State**:
- Icon color: `#A0A09B`
- Label color: `#A0A09B`

---

## Color Palette Reference

| Element | Color Name | Hex | Usage |
|---------|------------|-----|--------|
| Primary Green | OM Secondary | `#76B657` | Hero, CTAs, active states |
| Primary Teal | OM Primary | `#429479` | Protection icon gradient |
| Primary Dark | OM Dark | `#1A1A1A` | Body text, titles |
| Subtle Text | Ink/Subtle | `#A0A09B` | Labels, secondary text |
| Body Text | Ink/Strong | `#464647` | Body copy |
| Background | Neutral/5 | `#FAFAFE` | Card backgrounds |
| Border | Neutral/30 | `#E3E3E1` | Borders, dividers |
| Success Green | Status/Success/10 | `#ECF9EE` | Nudge background |
| Yu Brand | Primary/100 | `#E30D76` | Yu logo |
| White | Ink/White | `#FFFFFF` | Backgrounds, cards |

---

## Typography Reference

| Element | Font | Size | Weight | Line Height | Letter Spacing |
|---------|------|------|--------|-------------|----------------|
| Hero Title | Bariol | 28px | 700 | 32px | 1px |
| Section Title | Bariol | 20px | 700 | 24px | 0.8px |
| Card Title | Bariol | 18px | 700 | 24px | 0px |
| Greeting | Bariol | 16px | 400 | 24px | 0px |
| Card Value | Bariol | 32px | 700 | 40px | 0px |
| Stat Value | Bariol | 20px | 700 | 24px | 0px |
| Body Text | Bariol | 14px | 400/700 | 20px | 0px |
| Label | Bariol | 12px | 400/700 | 16px | 0.4px |
| Small Label | Bariol | 10px | 400/700 | 16px | 0.4px |

---

## Spacing System

**Vertical Spacing**:
- Header: 0px top
- Hero: 0px top (continues from header)
- Quick Stats: -8px top (overlaps hero)
- Content sections: 32px gap
- Cards: 16px gap between cards
- Internal card elements: 12-16px gap
- Bottom nav: 80px reserved space

**Horizontal Spacing**:
- Container: 375px total width
- Content padding: 24px left/right
- Content width: 327px
- Card padding: 20px
- Grid gap: 12px

**Everything follows 8px grid**: 8, 16, 24, 32, 40, 48, etc.

---

## Component States

### Value Cards
**Default**: White background, `#E3E3E1` border
**Hover**: Shadow 0 4px 12px rgba(0,0,0,0.08)
**Active**: Border → `#76B657`

### Action Tiles
**Default**: White, `#E3E3E1` border
**Hover**: Border → `#76B657`, subtle shadow
**Active**: Background → `#FAFAFE`

### Buttons
**Default**: White, `#E3E3E1` border
**Hover**: Border → `#76B657`, text → `#76B657`
**Active**: Background → `#FAFAFE`

### Bottom Nav
**Inactive**: Gray icon + label (`#A0A09B`)
**Active**: Green icon + label (`#76B657`)

---

## Data Integration Points

### Dynamic Values
```javascript
{
  // User
  user_first_name: "Sarah",
  time_of_day: "morning", // morning/afternoon/evening
  
  // Quick Stats
  growth_ytd: "+12.3%",                    // year-to-date growth
  total_value: "R1,025k",                  // pension + cash value of risk
  protection_status: "✓ Protected",         // or "⚠️ Review needed"
  
  // Retirement Card
  pension_balance: "R75,193",
  pension_growth_monthly: "+R324",
  pension_projected_retirement: "R450k+",  // AI calculation
  
  // Protection Card
  life_cover: "R850k",
  disability_cover: "R425k",
  funeral_cover: "R50k",
  protection_adequacy: "well protected",    // or "could be improved"
  
  // Recent Activity
  activities: [
    { type: "contribution", amount: "R324", time: "Today, 09:30" },
    { type: "yucoins", amount: "15", time: "Yesterday" },
    { type: "growth", amount: "R1,245", time: "This week" }
  ],
  
  // Nudge
  nudge_message: "One small change could improve your future",
  nudge_action: "/insights/recommendations"
}
```

### Personalization Hooks
- **Greeting**: Time-based (morning/afternoon/evening) + name
- **Total Value**: Pension balance + actuarial present value of risk benefits
- **Nudge**: AI-generated based on:
  - Recent activity patterns
  - Life stage
  - Contribution levels
  - Protection gaps
- **Protection Status**: ✓ if adequate, ⚠️ if gaps detected

---

## Behavioral Design Elements

### 1. **Unified Value Framing**
- Quick stats show **total value** across pension + protection
- Retirement and risk cards equal visual weight
- Combined activity feed (not separate tabs)

**Why it works**: Breaks down product silos. Member sees "one financial picture."

### 2. **Positive Framing**
- "Your future income" (not "pension pot")
- "Your family protection" (not "risk policy")
- "Building towards..." (progress, not gap)
- "You're well protected" (affirmation)

**Why it works**: Positive language increases engagement and reduces anxiety.

### 3. **Optional, Non-Intrusive Actions**
- Action tiles shown but not pushed
- Nudge is curiosity-driven ("See what")
- All CTAs are optional (never "You must")

**Why it works**: Respects member autonomy. No sales pressure = trust.

### 4. **Progress Indicators**
- Growth shown with up arrows + green color
- Monthly increase highlighted
- Retirement projection shown (future vision)

**Why it works**: Progress = motivation. Seeing growth encourages continued contribution.

### 5. **Social Proof (Subtle)**
- "People like you often add GAP cover" (optional copy)
- Protection adequacy compared to similar profiles (optional)

**Why it works**: Peer comparison influences behavior without pressure.

---

## Accessibility Notes

1. **Color Contrast**:
   - All text meets WCAG AA standards
   - Green on white: 4.5:1+
   - Dark text on light: 7:1+

2. **Touch Targets**:
   - All interactive elements: 44px+ minimum
   - Bottom nav icons: 24px visible, 48px tap area
   - Cards: Entire card tappable

3. **Screen Reader**:
   - Semantic HTML (h1, h2, section)
   - Alt text for icons
   - ARIA labels for navigation

4. **Cognitive Load**:
   - Only 2 main value cards (not overwhelming)
   - 4 optional actions (manageable)
   - Clear visual hierarchy

---

## Key Messaging

### Do Say:
✅ "Your financial home"
✅ "Your future income" + "Your family protection"
✅ "You're well protected"
✅ "Building towards..."
✅ "One small change could improve your future"
✅ "More ways to grow"

### Don't Say:
❌ "Your products"
❌ "Pension fund" or "Risk policy"
❌ "You need to..."
❌ "Act now!"
❌ "Don't miss out"
❌ "Upgrade required"

---

## Success Metrics (Post-Launch)

If this screen performs well, we'd expect:
- **Daily active users**: 60%+ return to home screen daily
- **Card engagement**: 30%+ click into value cards
- **Nudge click-through**: 15-20% explore suggestions
- **Optional actions**: 10-15% explore at least one tile
- **Session duration**: 45-90 seconds average
- **Satisfaction**: "This feels like my home" sentiment

---

## Design Rationale Summary

This screen is designed to:

1. **Break Down Silos**: Retirement + protection = one unified view
2. **Create Emotional Connection**: "Your financial home" = belonging
3. **Reduce Complexity**: Simple language, clear hierarchy
4. **Empower Choice**: Everything optional, nothing forced
5. **Show Progress**: Growth indicators = motivation
6. **Enable Discovery**: Optional actions lightly shown

**This isn't a product dashboard—it's a personal financial home where members feel secure, informed, and in control.**

---

*Document created: February 3, 2026*  
*Screen: A - Unified Member Home*  
*Type: Anchor Screen (Most Important)*  
*Designer: Amit*  
*Project: 10X ❤️ Yu Unified Engagement Layer*
