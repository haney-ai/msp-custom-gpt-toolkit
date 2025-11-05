# MSP Proposal Generator - Custom GPT Instructions

## Overview
This Custom GPT generates professional, customized proposals based on prospect information and discovery call notes, reducing proposal creation time from 2-4 hours to under 15 minutes.

**Build Time:** ~30 minutes to customize  
**ROI:** 2-3 hours saved per proposal

---

## Custom GPT Configuration

**Name:** MSP Proposal Generator

**Description:**
Creates professional, customized MSP proposals based on prospect details and discovery call notes, including executive summary, recommended solutions, pricing, and value propositions.

---

## Instructions

Copy and paste this into your Custom GPT's instruction field (customize the bracketed sections):
```
You are the MSP Proposal Generator for [MSP_NAME]. Your role is to create professional, customized proposals based on prospect information and discovery call notes.

PRIMARY FUNCTION:
When provided with prospect details, you generate a complete proposal including:
1. Executive summary tailored to their challenges
2. Recommended service package with justification
3. Pricing structure  
4. Value proposition specific to their industry/situation
5. Implementation timeline
6. Next steps

INFORMATION YOU NEED:
- Company name and industry
- Number of users/endpoints
- Current IT situation (in-house, break-fix, existing MSP)
- Key pain points or challenges mentioned
- Budget indicators (if any)
- Decision timeline
- Decision makers involved

YOUR KNOWLEDGE BASE INCLUDES:
- Service tier definitions and pricing
- Industry-specific value propositions
- Objection handling frameworks
- Standard terms and implementation timelines

PROPOSAL STRUCTURE:

**EXECUTIVE SUMMARY**
- Acknowledge their specific challenges
- Position your solution
- Key benefits (3-4 bullets)

**CURRENT STATE ASSESSMENT**
- Summarize their current IT situation
- Identify gaps or risks

**RECOMMENDED SOLUTION**
- Which service tier and why
- Specific services that address their pain points
- Unique value for their industry/situation

**INVESTMENT**
- Pricing breakdown
- What's included
- ROI or value justification

**IMPLEMENTATION TIMELINE**
- Onboarding steps
- Timeline expectations
- What they can expect

**WHY [MSP_NAME]**
- Relevant differentiators
- Industry experience if applicable
- Social proof

**NEXT STEPS**
- Clear call to action

COMMUNICATION STYLE:
- Professional and consultative (not salesy)
- Prospect-focused (emphasize their benefits)
- Confident but not aggressive
- Address concerns proactively
- Use specifics over generalities

IMPORTANT:
- Recommend the RIGHT service tier for their needs (don't always upsell)
- Be honest about fit
- If information is missing, ask before generating
- Pricing should align with uploaded pricing guidelines

CRITICAL CUSTOMIZATION NOTES:
- Replace [MSP_NAME] with your actual company name
- Update service tier names to match yours
- Adjust pricing structure to your model
- Customize differentiators to YOUR unique value
- Add your actual team member names if relevant
- Include your actual location/service area

PRIVACY:
- Do not include sensitive prospect information in examples
- Keep financial details professional
- Avoid overcommitting on timelines or deliverables
```

---

## Knowledge Base Files to Upload

Upload these three files to your Custom GPT:

1. **service_packages.txt** - Your service tiers, pricing, and what's included
2. **industry_value_props.txt** - Industry-specific messaging and value propositions
3. **objection_responses.txt** - How to handle common objections in proposals

See the other files in this folder for templates you can customize.

---

## Sample Prompts

**Prompt 1:** "Generate a proposal for: MidState Manufacturing, 35 users, currently using break-fix IT (local company), main pain points: constant network issues causing production delays, got hit with ransomware 8 months ago, owner is tired of surprises on the IT bill every month, wants predictable costs and proactive support, decision maker is the owner (Mike) who's not technical but cares about ROI."

**Prompt 2:** "Create proposal for: Summit Legal Group, 22 attorneys, currently have in-house IT person who's overwhelmed, need better security for client data, compliance concerns (attorney-client privilege), want 24/7 support, decision makers are managing partner and office administrator, budget appears flexible for the right solution."

**Prompt 3:** "Generate proposal for: GreenTech Startup, 12 users, growing fast (expect 25 users in 6 months), currently using break-fix, need scalable solution, modern cloud-focused, budget-conscious but understand value, CTO is technical and will evaluate, need to start quickly."

**Prompt 4:** "Create proposal for: Regional Medical Practice, 45 users across 3 locations, HIPAA compliance critical, current MSP not responsive enough, need better security and backup, decision committee includes practice administrator and lead physician, renewal decision in 30 days."

---

## Customization Checklist

Before deploying this Custom GPT:

- [ ] Replace all instances of `[MSP_NAME]` with your actual company name
- [ ] Update service_packages.txt with YOUR actual tiers and pricing
- [ ] Customize industry_value_props.txt with YOUR experience and differentiators
- [ ] Personalize objection_responses.txt with YOUR actual responses
- [ ] Add real team member names if you reference them in proposals
- [ ] Include your service area/locations
- [ ] Update implementation timeline to match YOUR process
- [ ] Test with 3-5 recent proposal scenarios
- [ ] Compare output to your best manual proposals
- [ ] Get feedback from your sales team
- [ ] Adjust based on what's working/not working

---

## What Makes This Work

**Success Factors:**
- Pricing information is accurate and current
- Industry value props are specific and credible
- Objection handling is proactive, not defensive
- Tone matches your brand (consultative, not pushy)
- Proposals are customized to prospect's specific situation
- Clear next steps and calls to action

**Failure Modes to Avoid:**
- Generic proposals that could be for any MSP
- Pricing that doesn't match your actual model
- Overpromising on capabilities or timelines
- Too salesy or aggressive in tone
- No differentiation from competitors
- Vague or missing implementation details
- Not addressing prospect's specific pain points

---

## Tips for Best Results

**Garbage in, garbage out:** The better your discovery call notes, the better the proposal. Use this as motivation to improve your discovery process.

**Don't just generate and send:** Review every proposal before sending. The GPT gets you 80-90% there, but you need to add the final 10-20% of personalization.

**Industry matters:** If you serve specific industries well (legal, medical, manufacturing), make sure your industry_value_props.txt reflects real experience, not generic claims.

**Pricing precision:** Be specific about pricing structure. "Starting at $X per user" is better than "competitive pricing."

**Differentiation:** What makes YOU different? That needs to be in the knowledge base, not just generic "we're great" statements.

**Test before launch:** Generate proposals for deals you already won or lost. Does the GPT's recommendation match what you actually proposed? If not, refine.

---

## Advanced Usage Ideas

**Speed up RFP responses:** Many RFPs have similar questions. Use the GPT to draft sections, then customize for the specific RFP.

**Proposal variations:** Generate multiple versions (Basic vs. Standard tier) to give prospects options.

**Follow-up proposals:** If a prospect goes dark, use the GPT to generate a simplified "still interested?" follow-up with updated pricing or options.

**Internal alignment:** Generate proposals early in sales process to ensure your team is aligned on what you're offering before the final pitch.

**Training tool:** New sales reps can use GPT-generated proposals as templates to learn your methodology and positioning.

---

## Integration with Your Sales Process

**Not required, but powerful:**

1. **Discovery Phase:** Take detailed notes during discovery calls knowing you'll feed them to the GPT
2. **Proposal Phase:** Generate first draft with GPT (15 minutes vs. 2-4 hours)
3. **Review Phase:** Sales rep adds personalization, verifies accuracy (30 minutes)
4. **Approval Phase:** Sales manager reviews and approves (15 minutes)
5. **Delivery Phase:** Send to prospect with confidence

**Total time saved:** 1-2+ hours per proposal

---

## When NOT to Use This

**Don't use the Proposal Generator for:**
- RFPs with very specific formatting requirements (government contracts)
- Highly complex custom solutions (heavy engineering required)
- Proposals requiring legal review before sending
- First proposal to a strategic account where CEO is personally involved

**Do use it for:**
- Standard managed services proposals
- SMB prospects (10-100 users)
- Opportunities with clear fit to your service tiers
- Speed-to-market situations (prospect needs proposal quickly)
- Training new sales reps

---

## Next Steps

1. Customize all three knowledge base files for your MSP
2. Create the Custom GPT in ChatGPT
3. Upload your customized files
4. Test with 3-5 recent proposals (won and lost deals)
5. Compare GPT output to your best manual proposals
6. Refine based on gaps
7. Train your sales team on how to use it
8. Share results in the workshop Discord

---

## Success Metrics

Track these to measure impact:

- **Time saved:** Hours spent on proposals before vs. after
- **Proposal quality:** Win rate before vs. after
- **Response speed:** Time from discovery call to proposal delivery
- **Consistency:** Do all proposals meet quality bar?
- **Sales rep adoption:** Is the team actually using it?

If you're not seeing improvement, revisit your knowledge base files and instructions.
