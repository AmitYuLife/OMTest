# 10X ❤️ Yu - Screen Design Index
## Complete Screen Library for 8-Slide Concept Deck

---

## 📱 Screens Completed

### ✅ Screen A: Unified Member Home (ANCHOR SCREEN)
**Status**: Complete  
**Priority**: Highest - Foundation of entire experience  
**Purpose**: Daily home base showing retirement + protection as one unified view

**Files**:
- `screen-a-unified-home.html` - Interactive mockup
- `SCREEN_A_DESIGN_SPEC.md` - Complete specification
- `SCREEN_A_README.md` - Quick start guide

**Key Features**:
- Unified value view (R1,025k total)
- Retirement card (R75k pension)
- Protection card (R850k life + R425k disability + R50k funeral)
- Behavioral nudge banner
- Optional action tiles (4)
- Recent activity feed
- Bottom navigation

**Design Highlights**:
- Personalized greeting ("Good morning, Sarah")
- "Your financial home" positioning
- Positive language ("Your future income" / "Your family protection")
- Equal visual weight for retirement + protection
- Gentle nudges, no sales pressure

---

### ✅ Screen D: Employee Exit Journey (CRITICAL SCREEN)
**Status**: Complete  
**Priority**: Critical - Highest economic value moment  
**Purpose**: Preserve member value at job change/exit

**Files**:
- `screen-d-employee-exit.html` - Interactive mockup
- `SCREEN_D_DESIGN_SPEC.md` - Complete specification (9,000+ words)
- `FIGMA_IMPLEMENTATION_GUIDE.md` - Step-by-step Figma instructions
- `REQUIREMENTS_CHECKLIST.md` - 99% compliance verification
- `VISUAL_LAYOUT_GUIDE.md` - Section-by-section breakdown
- `README.md` - Package overview

**Key Features**:
- Empathetic hero ("You're leaving your employer")
- What you've built summary (pension + life + disability)
- Three clear choices:
  1. ✅ Stay with 10X (RECOMMENDED)
  2. ⚠️ Cash out (WARNING with consequences)
  3. ➡️ Transfer elsewhere (NEUTRAL)
- Adviser support section
- Member-for-Life badge
- Clear CTA button

**Design Highlights**:
- Teal hero (calmer for transition moment)
- Behavioral nudges (green highlight, social proof)
- Transparent consequences (not fear tactics)
- Channel-supportive (adviser featured)
- Value visibility before decision

---

## 🎯 Screen Relationship Map

```
┌─────────────────────────────────────────────────────┐
│  SCREEN A: Unified Member Home (ANCHOR)             │
│  Daily return point - retirement + protection view  │
└─────────────────────┬───────────────────────────────┘
                      │
          ┌───────────┼───────────┐
          │           │           │
    ┌─────▼─────┐     │     ┌─────▼─────┐
    │ Screen B  │     │     │ Screen C  │
    │ Active    │     │     │ Life Event│
    │ Upsell    │     │     │ AI Insight│
    └───────────┘     │     └───────────┘
                      │
                ┌─────▼─────┐
                │ Screen D  │ ← CRITICAL
                │ Employee  │
                │ Exit      │
                └─────┬─────┘
                      │
          ┌───────────┼───────────┐
          │           │           │
    ┌─────▼─────┐     │     ┌─────▼─────┐
    │ Screen E  │     │     │ Screen F  │
    │ Individual│     │     │ Pre-Retire│
    │ Continue  │     │     │ Guidance  │
    └───────────┘     │     └───────────┘
                      │
                ┌─────▼─────┐
                │ Screen G  │
                │ Post-Ret  │
                │ Engage    │
                └───────────┘
```

---

## 📊 Design System Summary

### Reusable Components (Used Across Screens)

**Header Component** (92px)
- 10X logo + ❤️ + Yu square
- Hamburger menu + notification bell
- YuCoin counter
- Usage: All screens

**Hero Section** (260-300px)
- Rounded bottom (16px radius)
- Title + subtitle layout
- Optional illustration
- Color variations: Green (optimistic), Teal (transition)
- Usage: All main screens

**Value Cards** (White, bordered, 16px radius)
- Icon + category + title + arrow
- Value display
- Action buttons (optional)
- Usage: Screens A, B, C, F, G

**Nudge/Alert Banners**
- Colored background (green success, yellow warning)
- Icon + message + CTA
- Usage: Screens A, B, C, D

**Choice Cards** (Screen D specific)
- 3 variants: Recommended (green), Warning (yellow), Neutral (gray)
- Radio buttons
- Benefits/consequences lists
- Badges
- Usage: Screen D primarily, adaptable for other decision screens

**Action Tiles Grid**
- 2×2 or 2×3 grid
- Icon + title + subtitle
- Optional, non-intrusive
- Usage: Screens A, B

**Activity Feed**
- Icon + title + time + amount
- White or light background
- Usage: Screens A, G

**Bottom Navigation** (80px, fixed)
- 4 items: Home | Activity | Insights | Profile
- Active state highlighting
- Usage: Main navigation screens

---

## 🎨 Color Palette (Unified)

| Color | Hex | Usage |
|-------|-----|-------|
| OM Secondary (Green) | `#76B657` | Hero (optimistic), CTAs, success |
| OM Primary (Teal) | `#429479` | Hero (transition), protection |
| OM Dark | `#1A1A1A` | Body text, titles |
| Warning Yellow | `#FFD600` | Caution states |
| Success Light | `#ECF9EE` | Nudge backgrounds |
| Yu Brand | `#E30D76` | Yu logo, accents |
| Neutral Background | `#FAFAFE` | Card backgrounds |
| Neutral Border | `#E3E3E1` | Borders, dividers |
| Subtle Text | `#A0A09B` | Labels, secondary |
| White | `#FFFFFF` | Backgrounds, cards |

---

## 📝 Typography Scale (Unified)

| Element | Size | Weight | Line Height | Usage |
|---------|------|--------|-------------|-------|
| Hero Title | 28px | 700 | 32px | Main page titles |
| Section Title | 20px | 700 | 24px | Content section headers |
| Card Title | 18px | 700 | 24px | Card headers |
| Large Value | 32px | 700 | 40px | Financial amounts |
| Stat Value | 20px | 700 | 24px | Quick stats |
| Body | 14px | 400/700 | 20px | Body copy |
| Label | 12px | 400/700 | 16px | Labels, subtitles |
| Small Label | 10px | 700 | 16px | Badges, uppercase labels |

Font Family: **Bariol** (Bold 700, Regular 400)

---

## 📐 Spacing System (Unified)

All spacing follows **8px grid**:
- Micro: 4px (tight icon-to-text)
- Small: 8px (internal elements)
- Medium: 12px (card elements)
- Standard: 16px (between cards)
- Large: 24px (section gaps)
- Extra Large: 32px (major sections)
- Container padding: 24px (left/right)

---

## ⏱️ Implementation Timeline

### Phase 1: Foundation Screens (Week 1)
- ✅ Screen A: Unified Member Home
- ✅ Screen D: Employee Exit Journey
- ⏳ Screen B: Active Employment Upsell
- ⏳ Screen C: Life Event / AI Insight

### Phase 2: Continuation Screens (Week 2)
- ⏳ Screen E: Individual Continuation
- ⏳ Screen F: Pre-Retirement Guidance
- ⏳ Screen G: Post-Retirement Engagement

### Phase 4: Integration & Polish (Week 3)
- Prototype connections between screens
- Consistency check across all 8 screens
- Presentation deck creation
- Stakeholder review materials

**Critical Deadline**: February 9-16, 2026 (Hal visiting SA)

---

## 🎯 Screen Priority Matrix

| Screen | Priority | Status | Economic Impact | Design Complexity |
|--------|----------|--------|-----------------|-------------------|
| **A** | Highest | ✅ Complete | High (engagement) | Medium |
| **D** | Critical | ✅ Complete | Very High (preservation) | High |
| **B** | High | 🔜 Next | Medium (upsell) | Medium |
| **C** | High | 🔜 Next | Medium (AI value demo) | High |
| **E** | Medium | ⏳ Planned | High (continuation) | Low |
| **F** | Medium | ⏳ Planned | Medium (decision quality) | Medium |
| **G** | Medium | ⏳ Planned | Low (engagement) | Low |
| **H** | Low | ⏳ TBD | Low (storytelling) | Variable |

**Focus**: Screens A & D are complete (foundation + critical moment). Next: B & C for active member engagement.

---

## 📦 File Organization

```
screens/
├── INDEX.md                             [This file - master index]
│
├── screen-a-unified-home.html           [Screen A mockup]
├── SCREEN_A_DESIGN_SPEC.md             [Screen A specification]
├── SCREEN_A_README.md                  [Screen A quick start]
│
├── screen-d-employee-exit.html          [Screen D mockup]
├── SCREEN_D_DESIGN_SPEC.md             [Screen D specification]
├── FIGMA_IMPLEMENTATION_GUIDE.md       [Screen D Figma guide]
├── REQUIREMENTS_CHECKLIST.md           [Screen D compliance]
├── VISUAL_LAYOUT_GUIDE.md              [Screen D layout]
└── README.md                           [Screen D package overview]
```

---

## 🎤 Presentation Strategy

### For 10X COO Meeting

**Opening** (Screen A):
> "This is the foundation—where members return daily to see their retirement and protection working together as one financial home."

**Critical Moment** (Screen D):
> "This is the highest value moment—job change is when we typically lose members. This design makes preservation the obvious choice without pressure."

**The Flow** (Screens A→D):
> "Members start at their unified home (Screen A). When they change jobs, we meet them with clarity and empathy (Screen D). The relationship continues—Member-for-Life."

**The Ask**:
> "If we get these two screens right—the daily foundation and the critical exit moment—we'll transform member engagement and retention. The rest of the experience builds from here."

---

## 📈 Success Metrics Framework

### Screen A (Unified Home) Metrics:
- Daily active users: 60%+
- Card engagement: 30%+
- Nudge CTR: 15-20%
- Return rate: 70%+ within 7 days

### Screen D (Employee Exit) Metrics:
- Preservation rate: 70%+ choose Option 1
- Cash-out rate: <15% choose Option 2
- Time on screen: 60-120 seconds
- Adviser contact: 10-15%

### Combined Business Impact:
- Member retention: +25-30% vs industry
- Lifetime value: +40-50% through duration
- Preservation assets: Millions retained annually
- Cross-sell: +15-20% uptake on optional products

---

## 🔧 Technical Architecture

### Frontend Stack (Recommended):
- **Framework**: React Native (iOS + Android)
- **State Management**: Redux or Context API
- **Styling**: Styled Components or Tailwind
- **Navigation**: React Navigation
- **Data Fetching**: React Query
- **Analytics**: Segment + Mixpanel

### API Requirements:
- `GET /api/member/dashboard` (Screen A data)
- `GET /api/member/exit-options` (Screen D choices)
- `POST /api/member/preservation-choice` (Screen D selection)
- `GET /api/member/activities` (Activity feed)
- `GET /api/member/nudges` (AI-generated suggestions)

### Design Tokens:
- All colors, typography, spacing exported as JSON
- Shareable between Figma and code
- Version controlled

---

## ✅ Quality Checklist (All Screens)

Before considering any screen "done":

**Design**:
- [ ] Matches brand guidelines (10X + Yu)
- [ ] Follows design system (colors, typography, spacing)
- [ ] All spacing on 8px grid
- [ ] Touch targets ≥ 44px
- [ ] WCAG AA contrast ratios

**Content**:
- [ ] Simple language (no jargon)
- [ ] Positive framing
- [ ] South African context (Rand, local terms)
- [ ] Empathetic tone
- [ ] Member-first messaging

**Functionality**:
- [ ] All interactive elements clickable
- [ ] Navigation clear
- [ ] Error states designed
- [ ] Loading states designed
- [ ] Empty states designed

**Integration**:
- [ ] Connects to other screens logically
- [ ] API endpoints documented
- [ ] Data requirements specified
- [ ] Analytics events defined

---

## 🎨 Design Philosophy

### Core Principles Across All Screens:

1. **Member-First, Not Product-First**
   - Language: "Your future income" not "pension pot"
   - Structure: Unified view, not product silos
   - Actions: Optional, never forced

2. **Behavioral Intelligence**
   - Nudges that help, not push
   - Positive framing always
   - Progress indicators
   - Social proof (subtle)

3. **Transparency + Trust**
   - Show all options (Screen D)
   - Clear consequences
   - No hidden fees
   - Adviser support visible

4. **Continuity + Lifetime Value**
   - Member-for-Life positioning
   - Relationship beyond employment
   - Journey from onboarding to retirement
   - Nothing breaks when life changes

5. **Simplicity + Clarity**
   - 3 main actions per screen (max)
   - One primary message
   - Visual hierarchy clear
   - No overwhelming choice

---

## 🚀 Next Steps

### Immediate (This Week):
1. ✅ Review Screen A & D designs with team
2. ✅ Get feedback from Hal, Jaco
3. ⏳ Implement Screens A & D in Figma
4. ⏳ Start Screen B design

### Short-term (Next Week):
1. ⏳ Complete Screens B, C, E, F, G
2. ⏳ Create prototype flows
3. ⏳ Prepare presentation deck

### Before SA Meetings (Feb 9-16):
1. ⏳ All 7 screens complete
2. ⏳ Clickable prototype ready
3. ⏳ Presentation materials finalized
4. ⏳ Talking points prepared
5. ⏳ Demo rehearsed

---

## 📞 Team

- **Designer**: Amit (Screen execution, Figma)
- **Leadership**: Hal (Yu, visiting SA Feb 9-16)
- **10X Liaison**: Jaco (Requirements, feedback)
- **UX Expert**: George (NN pensions, currently unavailable)
- **Tool**: Pencil AI + Figma

---

## 💎 What Makes This Special

This isn't just 8 app screens. This is:

1. **A New Relationship Model**: Member-for-Life, not product customers
2. **Behavioral Science Applied**: Nudges that improve outcomes
3. **Unified Value View**: Breaking down product silos
4. **Critical Moment Design**: Preserving value at job change
5. **Channel-Supportive**: Technology + advisers working together
6. **Scalable Foundation**: Pattern for 10X's entire digital strategy

**We're not designing screens—we're designing the future of member engagement.**

---

*Master index created: February 3, 2026*  
*Project: 10X ❤️ Yu Unified Engagement Layer*  
*Screens Complete: 2/8 (A, D)*  
*Status: Foundation solid, continuing build*  
*Timeline: On track for Feb 9-16 meetings*

---

**Let's transform member relationships. Screen by screen. Moment by moment.** 🚀💚
