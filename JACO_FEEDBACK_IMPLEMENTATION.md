# Jaco's Feedback Implementation

## Summary
Based on Jaco's feedback from Feb 3, 2026, we've enhanced the 10X prototypes with critical SA-specific features that differentiate employer-provided vs self-purchased benefits, integrate the Two Pot System regulation, and add member certificate/beneficiary/claims functionality.

---

## 1. Employer vs Self-Purchased Benefits Distinction

### What was requested:
> "It will be good to show what your employer is giving you (pensions and group risk - life cover, income protection, lump sum disability, critical illness, funeral cover, education cover) versus what you bought yourself (retirement annuity, unit trust, tax free savings, life insurance, income protection, critical illness, funeral cover, education etc)."

### Implementation (Screen A - Unified Home):

**Employer-Provided Section:**
- Visual banner with 👔 icon: "Employer-provided benefits below"
- Clear labeling on retirement card: "FROM YOUR EMPLOYER" badge
- Clear labeling on protection card: "FROM YOUR EMPLOYER" badge

**Self-Purchased Section:**
- Renamed section to "Add to your financial plan"
- New banner with 💎 icon: "Personal investments & protection"
- Description: "Add your own savings and cover beyond what your employer provides. Tax-efficient and flexible."
- Includes cross-sell tiles for:
  - Retirement Annuity (RA)
  - Unit Trusts
  - Tax-Free Savings
  - Individual Life Cover
  - Coaching
  - Wellbeing

**Expanded Group Protection Coverage:**
The Yu Protection card now shows all 6 coverage types:
- Life cover: R850k
- Income protection: R15k/month
- Lump sum disability: R425k
- Critical illness: R300k
- Funeral cover: R50k
- Education cover: R100k

---

## 2. Two Pot System Integration

### What was requested:
> "A big new regulation that came out last year in SA is what we call the 'Two Pot System' where your pension is split into two pots and you are allowed to withdraw a pot earlier, but there are a lot of rules and tax implications around this. Obviously best is if you don't take it. Guidance and AI financial wellness learning will be great to work in."

### Implementation:

#### Screen A (Home) - Member View:
Shows Two Pot breakdown in retirement card:
- **Retirement Pot (locked):** R67,674 (90%)
- **Savings Pot (accessible):** R7,519 (10%)
- **Tip:** "Keep your savings pot for retirement to maximize your future income"

#### Screen C (AI Life Events) - Education:
Full AI-powered Two Pot System education module:

**🔒 Retirement Pot (90%): R67,674**
- Locked until retirement
- Grows tax-free
- This is your future security

**💰 Savings Pot (10%): R7,519**
- Can be withdrawn once per tax year
- But: 20-35% tax + lost compound growth
- **AI insight:** "Withdrawing R7,519 today = losing R45,000+ at retirement (compound growth over 30 years)"

#### Screen D (Employee Exit) - Critical Decision Point:
**Two Pot System Alert Box:**
- "Your R7,519 Savings Pot can be withdrawn, but there are tax implications"
- "Your R67,674 Retirement Pot stays protected for your future"
- **AI Recommendation:** "Members who preserve both pots typically have R186,000 more at retirement (due to compound growth + lower 10X fees)"

**Updated Cash-Out Option:**
- "Can only access Savings Pot (R7,519) without penalty"
- "Pay 20-35% tax immediately"
- Updated warning: "Two Pot System: Only R7,519 accessible. Cashing out your Retirement Pot means heavy tax penalties."

**Updated Preservation Option:**
- "Both pots preserved in 10X Preservation Fund"
- Clear messaging that full balance stays protected

---

## 3. Member Certificate, Beneficiaries & Claims

### What was requested:
> "In our SA app, we show you all the actual cover that you have with us (group protection) and you can see your member certificate and add / change your beneficiaries (which is a big thing) and you can also submit claims"

### Implementation (Screen A - Protection Card):

**Updated Card Actions:**
- ✓ **View certificate** - Access full member certificate
- ✓ **Update beneficiaries** - Manage beneficiary details (highlighted as important)
- ✓ **Submit claim** - Easy claim submission

**Protection Card Enhancements:**
- Shows all 6 coverage types with exact values
- "FROM YOUR EMPLOYER" badge for clarity
- Subtitle emphasizes value: "You're well protected—here's why →"

---

## SA Market Differentiation

These features are critical for the South African insurance market:

### Regulatory Compliance:
- Two Pot System (2025 regulation) fully integrated
- Tax implications clearly communicated
- AI-powered guidance discourages premature withdrawal

### Member Engagement:
- Transparency on employer vs self benefits builds trust
- Beneficiary management is culturally important in SA
- Claims process visibility increases utilization

### 10X Value Proposition:
- Fee savings quantified at every touchpoint
- "LOWEST FEES IN SA" badge on preservation
- Compound growth calculations show long-term impact
- Zero fees for 6 months on preservation

---

## Key Screens Updated

1. **Screen A (Unified Home):**
   - Employer vs self banners
   - Expanded protection coverage (6 types)
   - Two Pot breakdown
   - Certificate/beneficiaries/claims buttons

2. **Screen C (AI Life Events):**
   - Complete Two Pot System education
   - AI insights on compound growth impact
   - Tax implications clearly explained

3. **Screen D (Employee Exit):**
   - Two Pot System alert at critical moment
   - Updated all 3 choice options with Two Pot context
   - Expanded protection coverage
   - AI recommendation to preserve both pots

---

## Business Impact

### For 10X COO Meeting:
1. **Market-ready**: Shows understanding of SA regulatory environment
2. **Member-centric**: Addresses real SA member needs (beneficiaries, claims)
3. **Educational**: AI-powered financial wellness throughout
4. **Competitive**: Fee savings + Two Pot guidance = clear value proposition

### For Yu Partnership:
1. **Seamless integration**: Employer benefits + individual products
2. **Cross-sell strategy**: Clear path from employer to self-purchased
3. **Retention focus**: Preservation journey emphasizes continued coverage
4. **Compliance**: Two Pot System properly implemented

---

## Next Steps (If Needed)

### Potential Enhancements:
1. **Member certificate mockup** - Visual design of downloadable PDF
2. **Beneficiaries management flow** - Multi-step beneficiary update screens
3. **Claims journey** - Step-by-step claim submission process
4. **Two Pot calculator** - Interactive tool showing withdrawal impact
5. **Preservation decision tool** - Guided workflow for exit choices

### Integration Points:
- 10X API for real-time pot balances
- Yu claims API for group protection
- Beneficiary management system
- Digital certificate generation

---

## Technical Notes

- All HTML updates maintain consistent hero structure (72px top padding)
- Two Pot breakdown uses real 90/10 split
- Fee calculations consistent across all screens
- Visual hierarchy: employer benefits → education → self-purchased
- Mobile-first design (375px width) maintained

---

**Status:** ✅ Complete and pushed to GitHub  
**Commit:** `c178024` - "Add SA-specific features: employer vs self distinction, Two Pot System, expanded protection coverage, beneficiaries and claims"  
**Files Updated:** 3 (screen-a, screen-c, screen-d)  
**Lines Changed:** +140 insertions, -16 deletions
