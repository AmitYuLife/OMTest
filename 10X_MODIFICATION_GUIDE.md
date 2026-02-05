# 10X Prototype Modification Guide
## How Easy Is It to Adapt the Old Mutual Prototypes?

---

## TL;DR: Very Easy! 🚀

**Bottom line**: You already have all 8 screens built with the right structure, flow, and UX patterns. This is **primarily a rebrand + product swap**, not a rebuild.

**Estimated total time**: 15-20 hours (vs 80+ hours to build from scratch)

---

## What Makes This Easy

### 1. Same Core Product Structure ✅
Both partnerships are:
- Umbrella fund (retirement) + Group risk (protection)
- Focused on preservation at job change
- Cross-sell to individuals
- Lifecycle-based engagement

### 2. Same UX Patterns ✅
- Unified dashboard home
- Life event-triggered nudges
- 3-path choice architecture at exit
- Behavioral AI insights
- Timeline visualizations

### 3. Better Brand Fit (Actually Easier!) ✅
- 10X is more tech-forward than Old Mutual
- Simpler, cleaner aesthetic (less complex)
- More direct tone (easier to write)
- Digital-native story is more credible

---

## Modification Breakdown by Screen

### Screen A: Unified Member Home
**Time: 2 hours**

| Element | Old Mutual | 10X | Effort |
|---------|-----------|-----|--------|
| **Color scheme** | Old Mutual colors | Orange/coral accents | Find & replace |
| **Logo** | Old Mutual ❤️ Yu | 10X ❤️ Yu | Swap image |
| **Retirement section** | "Your pension" | "Your 10X retirement savings" | Text change |
| **Risk section** | Old Mutual group risk | Yu protection products | Text change |
| **New element** | - | Fee savings callout | Add 1 card |
| **Cross-sell tiles** | GAP, coaching | RA, unit trusts, tax-free | Replace 3 tiles |

**Complexity**: LOW - mostly text and styling changes

---

### Screen B: Active Employment Upsell
**Time: 1.5 hours**

| Element | Change | Effort |
|---------|--------|--------|
| **Life event prompts** | Keep same | None |
| **Product options** | Add: RA, unit trusts, tax-free savings | Update product cards |
| **Risk products** | Change to Yu's own products | Text updates |
| **Fee messaging** | Add fee comparison | New component |
| **Tone** | Simplify further | Copy edit |

**Complexity**: LOW - add products, adjust messaging

---

### Screen C: AI Life Event Insights
**Time: 2 hours**

| Element | Change | Effort |
|---------|--------|--------|
| **Investment strategy** | Change to index-based language | Copy rewrite |
| **Scenarios** | Add fee impact over time | Modify visualization |
| **Branding** | "Based on 10X data..." | Text change |
| **Visualization style** | Cleaner, more minimal | CSS adjustments |

**Complexity**: MEDIUM - visualization tweaks needed

---

### Screen D: Employee Exit (CRITICAL)
**Time: 2.5 hours**

| Element | Change | Effort |
|---------|--------|--------|
| **Preservation option** | "Preserve with 10X" | Text change |
| **Fee comparison** | More prominent (10X strength) | Enhance existing component |
| **Risk continuation** | Yu individual life product | Update product description |
| **Adviser messaging** | Less adviser-dependent | Simplify copy |
| **Path comparison** | Add fee impact to 3 paths | Enhance table |

**Complexity**: MEDIUM - most important screen, needs careful attention to 10X value props

---

### Screen E: Post-Employment Individual
**Time: 1.5 hours**

| Element | Change | Effort |
|---------|--------|--------|
| **Individual products** | Retirement annuity, unit trusts, tax-free | Add product cards |
| **Yu products** | Individual life insurance | New product card |
| **Messaging** | "Still saving on fees" | Add callout |
| **Dashboard** | Same structure | No change |

**Complexity**: LOW - add products, update copy

---

### Screen F: Pre-Retirement Guidance
**Time: 1.5 hours**

| Element | Change | Effort |
|---------|--------|--------|
| **Investment philosophy** | Index-based, long-term | Copy update |
| **Fee visualization** | Compound fee savings over time | New chart |
| **Calculator link** | "Powered by 10X calculator" | Add CTA |
| **Transition prep** | Living annuity messaging | Text update |

**Complexity**: LOW - mostly copy changes

---

### Screen G: Post-Retirement
**Time: 1.5 hours**

| Element | Change | Effort |
|---------|--------|--------|
| **Product** | Living annuity (10X) | Text change |
| **Drawdown strategy** | Align with 10X philosophy | Copy update |
| **Fee transparency** | Continue fee savings message | Add component |
| **Yu products** | Optional cover continuation | Text update |

**Complexity**: LOW - mostly copy and branding

---

### Screen H: Lifecycle Journey Map
**Time: 2 hours**

| Element | Change | Effort |
|---------|--------|--------|
| **Timeline products** | Map 10X products at each stage | Update product labels |
| **Risk products** | Yu products throughout | Update labels |
| **Key message** | Low fees throughout life | Add messaging |
| **Visual style** | Cleaner, more minimal | Style adjustments |

**Complexity**: LOW-MEDIUM - update all product labels and styling

---

## Total Time Estimate

| Task | Time |
|------|------|
| Screen A | 2h |
| Screen B | 1.5h |
| Screen C | 2h |
| Screen D | 2.5h |
| Screen E | 1.5h |
| Screen F | 1.5h |
| Screen G | 1.5h |
| Screen H | 2h |
| **Total screens** | **15h** |
| Testing & polish | 2h |
| Demo flow setup | 1h |
| Documentation | 1h |
| **GRAND TOTAL** | **19 hours** |

---

## What You Need to Get Started

### Brand Assets
- [ ] 10X logo (SVG or high-res PNG)
- [ ] 10X color codes
  - Primary orange/coral: #[TBD]
  - Secondary colors: #[TBD]
- [ ] 10X font specifications (looks like a clean sans-serif)
- [ ] Any 10X brand guidelines (if available)

### Product Information
- [ ] 10X umbrella fund details
- [ ] 10X preservation fund info
- [ ] 10X living annuity details
- [ ] Retirement annuity (RA) details
- [ ] Unit trust options
- [ ] Tax-free investment details
- [ ] Yu's group risk product specs
- [ ] Yu's individual life insurance details (if ready)

### Technical
- [ ] 10X website for reference (already reviewed)
- [ ] Access to existing Old Mutual prototype files (you have these)
- [ ] Development environment set up

---

## Step-by-Step Modification Process

### Phase 1: Foundation (2 hours)
1. Create new directory: `/screens-10x/`
2. Copy all 8 HTML files from `/screens/`
3. Update global CSS variables:
   - Primary color → 10X orange
   - Secondary colors
   - Font families
4. Replace logo files
5. Test one screen (Screen A) to validate approach

### Phase 2: Screen-by-Screen (13 hours)
For each screen:
1. Update branding elements (logo, colors)
2. Replace product names and descriptions
3. Adjust copy to 10X tone
4. Add fee transparency elements
5. Update cross-sell options
6. Test responsive behavior
7. Cross-check against design brief

### Phase 3: Polish & Integration (4 hours)
1. Consistency check across all screens
2. Navigation testing
3. Demo flow setup (for COO presentation)
4. Mobile responsiveness check
5. Create presentation notes
6. Documentation updates

---

## Key Advantages of 10X Adaptation

### 1. Simpler Aesthetic
10X's brand is cleaner and more minimal than Old Mutual's traditional approach. This means:
- Less complex styling needed
- Fewer visual elements to manage
- Faster rendering
- More modern feel

### 2. Better Tech Story
10X is a tech company, so:
- Integration narrative is more credible
- Digital-first experience feels authentic
- Less need to explain "why app"
- API/platform story is natural

### 3. Clearer Messaging
10X's brand is built on transparency and simplicity:
- Copy is more direct
- Less corporate language needed
- Fee focus gives clear differentiation
- Easier to write compelling content

### 4. Stronger Differentiation
10X + Yu combination is unique:
- No one else has this in SA market
- Low fees + behavioral engagement = unbeatable
- Tech-forward + group risk = new category

---

## Potential Challenges (Minor)

### Challenge 1: Fee Transparency Components
**Issue**: Need to add fee comparison elements throughout  
**Solution**: Create reusable component once, use everywhere  
**Time**: 1 hour to build, then copy/paste  

### Challenge 2: Product Descriptions
**Issue**: Need details on 10X products and Yu risk products  
**Solution**: Use website copy + product sheets  
**Time**: Research time only, already built into estimates  

### Challenge 3: Individual Life Insurance
**Issue**: Yu creating these products - might not be fully defined  
**Solution**: Use placeholder copy, update later  
**Time**: Minimal - can iterate  

### Challenge 4: Brand Assets
**Issue**: May need to request 10X logos and brand guidelines  
**Solution**: Can extract from website initially, refine later  
**Time**: Website extraction is immediate  

---

## Comparison: Build from Scratch vs Modify

| Aspect | From Scratch | Modify Old Mutual |
|--------|-------------|-------------------|
| **Structure/Layout** | 20-30 hours | ✅ Done |
| **UX patterns** | 15-20 hours | ✅ Done |
| **Interactions** | 10-15 hours | ✅ Done |
| **Responsive design** | 10-15 hours | ✅ Done |
| **Content strategy** | 8-10 hours | ✅ Done |
| **Behavioral logic** | 5-8 hours | ✅ Done |
| **Rebranding** | - | 8-10 hours |
| **Product swap** | - | 5-7 hours |
| **Copy updates** | - | 4-5 hours |
| **Testing** | 5 hours | 2 hours |
| **TOTAL** | **73-103 hours** | **19-24 hours** |

**Savings**: 54-84 hours (75-80% time reduction)

---

## Pre-Meeting Checklist

For next Friday's COO meeting:

### Must Have
- [ ] All 8 screens rebranded to 10X
- [ ] Key products mapped (10X retirement + Yu risk)
- [ ] Fee transparency messaging added
- [ ] Demo flow working (can click through)
- [ ] Mobile-friendly (COO might view on phone)

### Nice to Have
- [ ] 10X actual brand assets (vs website extraction)
- [ ] Real product details (vs placeholder copy)
- [ ] Integration narrative slide deck
- [ ] Business case one-pager

### Can Come Later
- [ ] Pixel-perfect refinements
- [ ] All cross-sell products fully detailed
- [ ] Yu individual life insurance specifics
- [ ] Final copy polish

---

## Recommended Approach

### Week 1 (This Week)
**Goal**: Get 10X version to 80% quality

**Monday-Tuesday**: 
- Extract 10X brand from website
- Modify Screens A, D, H (most important 3)
- Test demo flow

**Wednesday-Thursday**:
- Complete remaining 5 screens
- Add fee transparency throughout
- Polish and test

**Friday**:
- Final review and adjustments
- Prepare demo notes
- Send preview link

### Week 2 (Meeting Week)
**Monday-Thursday**:
- Incorporate any feedback
- Refine based on new information
- Prepare presentation materials

**Friday**:
- COO meeting with working prototype
- Gather feedback and next steps
- Plan iteration

---

## Why This Will Work

### 1. Proven Foundation
The Old Mutual prototype validates:
- The unified pensions + risk concept works
- The 8-screen flow is comprehensive
- The UX patterns are sound
- The behavioral approach resonates

### 2. Better Brand Fit
10X is actually an **easier** brand to work with:
- Simpler visual language
- More direct messaging
- Tech-forward positioning
- Modern aesthetic

### 3. Clear Differentiation
10X + Yu offers something unique:
- Lowest fees in market (10X)
- Best group risk + engagement (Yu)
- Tech-enabled seamlessness
- No competitor has this combination

### 4. Natural Partnership
Both companies are:
- Tech-forward
- Disruptive in their markets
- Focused on member value
- Transparent and simple

---

## Bottom Line

**Question**: "How easy is it to just use a similar prototype and modify for 10x?"

**Answer**: Very easy. 

You're looking at **15-20 hours of work** vs **80-100 hours from scratch**. The hard parts (structure, UX, flow, interactions, responsive design) are all done. This is primarily:

1. **Rebrand** (8-10 hours): Colors, logo, typography, tone
2. **Product swap** (5-7 hours): Replace Old Mutual products with 10X equivalents
3. **Messaging enhance** (4-5 hours): Add fee transparency, simplify copy
4. **Polish** (2-3 hours): Testing and refinement

The 10X version will actually be **simpler and cleaner** than Old Mutual because:
- 10X brand is more minimal
- Less corporate language needed
- Tech story is more credible
- Fee focus gives clear differentiation

**Recommendation**: Start with Screen A (home), Screen D (exit), and Screen H (lifecycle) for the COO meeting. If those three are strong, the story is told. Complete the other 5 screens after if the meeting goes well.

---

*Ready to start modifications whenever you are!*
