# Examples: User Feedback Analysis


## 📝 Prompt Example
**Input:** 

---

## 💡 Output Examples
10 examples representing different use cases

### Example 1: Enterprise Customer - Critical Integration Issue

**Customer Feedback:**
"Our entire sales team (45 people) can't access customer data in Salesforce because the sync has been broken for 3 days. We're losing deals because reps don't have updated contact info. This is costing us real money. We pay $15K/month for this product and expect better reliability. If this isn't fixed by EOD, we need to discuss our contract."

**AI Analysis Output:**
1. **Primary Theme:** Salesforce integration failure causing complete data sync breakdown for large sales team
2. **Urgency:** Critical
3. **Category:** Bug (Integration)
4. **Sentiment:** Negative (highly frustrated, threatening churn)
5. **Action Recommended:** 
   - **IMMEDIATE:** Escalate to engineering lead for emergency fix
   - Alert customer success team for proactive outreach
   - Investigate root cause of 3-day sync failure
   - Provide hourly updates to customer until resolved
   - Post-resolution: Review SLA compliance and consider service credit
6. **Priority Score:** **10/10**

**Additional Context:**
- Customer Tier: Enterprise ($15K MRR)
- User Count: 45 seats affected
- Churn Risk: HIGH - explicit threat to review contract
- Business Impact: Direct revenue loss (lost deals)
- Time Sensitive: EOD deadline mentioned

---

### Example 2: Feature Request - SSO Authentication

**Customer Feedback:**
"Hey team! Love the product so far. Our IT security team is asking about SSO support - we use Okta for everything else. Not a blocker right now since we're still in pilot mode with 5 users, but we'll need this before rolling out to the full product team (30 people) next quarter. Any timeline on when SSO might be available?"

**AI Analysis Output:**
1. **Primary Theme:** Request for SSO/SAML authentication support (specifically Okta) needed for enterprise rollout
2. **Urgency:** **Medium**
3. **Category:** **Feature Request** (Authentication/Security)
4. **Sentiment:** **Positive** (satisfied with product, polite request)
5. **Action Recommended:**
   - Add to enterprise feature roadmap
   - Schedule call to understand full security requirements
   - Share current roadmap timeline if SSO is planned
   - Flag as expansion opportunity (5 → 30 seats)
   - Document in "Enterprise Blockers" tracking list
6. **Priority Score:** **7/10**

**Additional Context:**
- Customer Tier: Growth/Mid-Market (5 current seats)
- Expansion Potential: 6x seat growth pending this feature (30 total)
- Timeline: Next quarter (3 months) - medium urgency
- Churn Risk: LOW - currently satisfied, proactive request
- Common Request: SSO is frequently requested by enterprise customers

---

### Example 3: UX Friction - Dashboard Confusion

**Customer Feedback:**
"I've been using the dashboard for 2 weeks and I'm still confused about what the 'Insights' section is showing me. The numbers don't match what I see when I click through to the actual feedback. Also, why are there sometimes 3 different sentiment scores? Which one should I trust? The UI looks nice but I'm spending more time trying to understand it than actually using it."

**AI Analysis Output:**
1. **Primary Theme:** Dashboard comprehension issues - unclear metrics display and conflicting sentiment data causing user confusion
2. **Urgency:** **Medium**
3. **Category:** **UX Issue** (Dashboard/Analytics)
4. **Sentiment:** **Neutral** (frustrated but not angry, wants to use product successfully)
5. **Action Recommended:**
   - Schedule user research session to observe dashboard usage
   - Audit Insights section for data accuracy bugs
   - Review sentiment score calculation and display logic
   - Add in-app tooltips/help text to explain metrics
   - Create "Dashboard Guide" help article
   - Consider A/B test of simplified dashboard layout
6. **Priority Score:** **6/10**

**Additional Context:**
- User Experience: 2 weeks (still in onboarding phase)
- Issue Type: Onboarding/comprehension rather than blocking bug
- Pattern Recognition: May indicate broader UX issues affecting other users
- Quick Wins: Documentation and tooltips can help immediately
- Deeper Fix: May need dashboard redesign based on user research

---

### Example 4: Positive Feedback with Enhancement Suggestion

**Customer Feedback:**
"The AI categorization is seriously impressive! It's saving me probably 6-7 hours every week. I especially love how it catches patterns I would have missed manually. One thing that would make it even better - could you add a way to create custom categories specific to our product? We have some unique feature areas that don't fit the default categories perfectly. Otherwise, this is exactly what we needed!"

**AI Analysis Output:**
1. **Primary Theme:** Strong satisfaction with AI categorization, with enhancement request for custom category taxonomy
2. **Urgency:** **Low**
3. **Category:** **Feature Request** (Enhancement)
4. **Sentiment:** **Positive** (enthusiastic, highly satisfied)
5. **Action Recommended:**
   - Capture as testimonial/case study material
   - Add custom categories to product roadmap (already planned feature)
   - Share roadmap timeline with user to maintain enthusiasm
   - Request permission to feature as reference customer
   - Follow up in 2 weeks to gather more detailed use case examples
6. **Priority Score:** **5/10**

**Additional Context:**
- Time Savings: 6-7 hours/week (validates core value prop)
- User Satisfaction: HIGH - potential advocate/reference customer
- Feature Request: Custom categories (already on roadmap - can deliver good news)
- Marketing Opportunity: Strong testimonial about AI quality
- Retention Risk: VERY LOW - highly engaged power user

---

### Example 5: Multi-Issue Support Ticket

**Customer Feedback:**
"Having several problems: 1) Zendesk integration stopped working yesterday, showing 'Authentication Failed' error. I tried reconnecting but same issue. 2) The search function doesn't find tickets I know exist - searched for 'billing issue' and got 0 results but I can see 15 tickets with that phrase when I browse manually. 3) Minor thing but the export to CSV cuts off long feedback text after 100 characters. Need full text for reports."

**AI Analysis Output:**
1. **Primary Theme:** Multiple technical issues - broken Zendesk auth, search functionality failing, CSV export truncation
2. **Urgency:** **High**
3. **Category:** **Bug** (Multiple: Integration + Search + Export)
4. **Sentiment:** **Negative** (frustrated by multiple blocking issues)
5. **Action Recommended:**
   - **P0 - Zendesk Auth:** Investigate authentication failure immediately (may affect multiple users)
   - **P0 - Search Bug:** Critical functionality failure - test search with "billing issue" query to reproduce
   - **P1 - CSV Export:** Add to sprint backlog, implement full text export option
   - Assign customer success manager for proactive communication
   - Create single support ticket tracking all three issues
   - Provide workarounds where possible (manual CSV formatting for #3)
6. **Priority Score:** **9/10**

**Additional Context:**
- Issue Count: 3 separate bugs (indicates quality concerns)
- Blocker Status: Issues #1 and #2 are workflow-blocking
- User Impact: Unable to perform core tasks (integration, search)
- Response SLA: High priority - respond within 2 hours with action plan
- Pattern Check: Verify if Zendesk auth issue is affecting other users

---

### Example 6: Pricing/Commercial Question

**Customer Feedback:**
"Quick question - we're currently on the Starter plan ($99/mo) but we're about to hit the 1,000 feedback items per month limit. What happens when we exceed that? Do items just stop syncing? Also, our team is growing and we'll need to add 3 more PM seats next month. Can we get volume pricing since we're scaling up quickly?"

**AI Analysis Output:**
1. **Primary Theme:** Account limit approaching (usage ceiling) + expansion inquiry (seat addition) + pricing negotiation request
2. **Urgency:** **Medium**
3. **Category:** **Other** (Commercial/Billing)
4. **Sentiment:** **Neutral** (practical question, growth signal)
5. **Action Recommended:**
   - **Route to Sales/CS team** (not a product issue)
   - Proactive outreach: contact before they hit limit
   - Explain overage policy and upgrade options
   - Prepare custom quote for increased seats + higher tier
   - Flag as expansion/upsell opportunity
   - Add in-product usage alerts for approaching limits (product improvement)
6. **Priority Score:** **6/10**

**Additional Context:**
- Customer Health: POSITIVE - growing usage indicates value
- Revenue Opportunity: Upsell from $99/mo Starter to Growth/Pro tier
- Seat Expansion: +3 seats (33-43% growth)
- Urgency Driver: Approaching hard limit - time-sensitive
- Product Gap: No proactive alerting before hitting limits (add to backlog)

---

### Example 7: Competitive Comparison

**Customer Feedback:**
"We're evaluating your product vs. Productboard and Canny. I like your AI features better, but both competitors let you create public roadmaps that customers can vote on. That's really important for our workflow since we want customers to see we're listening. Do you have anything like that planned? If not, that might be a dealbreaker for us unfortunately."

**AI Analysis Output:**
1. **Primary Theme:** Competitive evaluation - requesting public roadmap + voting feature that exists in Productboard and Canny
2. **Urgency:** **High**
3. **Category:** **Feature Request** (Competitive Gap)
4. **Sentiment:** **Neutral** (interested but will churn without feature)
5. **Action Recommended:**
   - **URGENT:** Schedule demo call to understand full requirements
   - Review competitive positioning and roadmap priorities
   - If public roadmap is on roadmap: share timeline and commit date
   - If not planned: assess strategic importance based on deal size
   - Consider custom solution or partnership if high-value prospect
   - Document as competitive loss if feature can't be delivered
   - Track pattern: how often does this feature cause lost deals?
6. **Priority Score:** **8/10**

**Additional Context:**
- Customer Status: Prospective (in evaluation phase)
- Churn Risk: HIGH - explicit "dealbreaker" language
- Competitive Intel: Productboard and Canny have feature parity here
- Deal Status: At risk of loss to competitor
- Strategic Decision: Is public roadmap core to product strategy?
- Revenue Impact: Depends on prospect size (escalate if enterprise)

---

### Example 8: Performance Complaint

**Customer Feedback:**
"The dashboard is really slow lately. Takes 15-20 seconds to load, sometimes times out completely. This is with only about 500 feedback items so I can't imagine how slow it'll be when we have thousands. Using Chrome on a MacBook Pro with good internet, so not a local issue. Makes it hard to use during meetings when I need to pull up data quickly."

**AI Analysis Output:**
1. **Primary Theme:** Dashboard performance degradation - slow load times (15-20s) and timeouts affecting usability
2. **Urgency:** **High**
3. **Category:** **Bug** (Performance/Infrastructure)
4. **Sentiment:** **Negative** (frustrated, concerned about future scalability)
5. **Action Recommended:**
   - **Engineering:** Investigate dashboard query performance immediately
   - Reproduce issue with similar data volume (500 items)
   - Check server logs for timeouts and slow queries
   - Review database indexes and query optimization
   - Implement loading states/progress indicators short-term
   - Add performance monitoring for dashboard load times
   - Follow up with user once fix is deployed
6. **Priority Score:** **8/10**

**Additional Context:**
- Performance Baseline: Should load in < 2 seconds (per PRD requirement)
- Current Performance: 15-20 seconds (7-10x slower than target)
- Scale Concern: User worried about future scalability
- Use Case Impact: Blocking meeting usage (high-value use case)
- Technical Debt: May indicate broader performance issues
- User Environment: Standard setup (Chrome, MacBook) - not edge case

---

### Example 9: Onboarding Friction

**Customer Feedback:**
"Just signed up and went through onboarding. I connected my Zendesk account but now what? The dashboard is empty and says 'No feedback found.' How long does it take to sync? There's no progress bar or anything so I don't know if it's working or broken. Been waiting 30 minutes. Also, the onboarding tutorial skipped over how to actually set up categories."

**AI Analysis Output:**
1. **Primary Theme:** Poor onboarding experience - unclear sync status, no progress indicators, incomplete tutorial causing new user confusion
2. **Urgency:** **Medium**
3. **Category:** **UX Issue** (Onboarding)
4. **Sentiment:** **Negative** (confused, frustrated, at-risk new user)
5. **Action Recommended:**
   - **Short-term:** Manually check user's integration status and help complete setup
   - **Product fixes:**
     - Add sync progress indicator with estimated time
     - Show "Syncing X of Y items" status updates
     - Improve onboarding tutorial to cover category setup
     - Add help text explaining typical sync duration (15 mins for 90 days)
     - Consider starting tutorial after first feedback arrives
   - Track new user activation metrics - may indicate broader onboarding problem
6. **Priority Score:** **7/10**

**Additional Context:**
- User Stage: Day 0 (first session) - critical activation moment
- Churn Risk: HIGH - poor first impression, may abandon product
- Expected Sync Time: 15-30 minutes for 90-day Zendesk backfill
- UX Gap: No feedback during wait time (anxiety-inducing)
- Impact: Affects ALL new users - high-impact fix
- Quick Win: Progress indicator can be implemented rapidly

---

### Example 10: Feature Enhancement from Power User

**Customer Feedback:**
"Been using this daily for 3 months now, absolutely love it. Feature idea: could you add the ability to tag specific feedback items to Jira tickets? Right now I manually copy-paste feedback into Jira descriptions when creating tickets. If I could just click 'Link to Jira' and search for my ticket, that would save tons of time and keep everything connected. Also, being able to see how much feedback is linked to each ticket would help prioritize the backlog. Just a thought!"

**AI Analysis Output:**
1. **Primary Theme:** Feature enhancement request for Jira integration - link feedback to tickets for better traceability and prioritization
2. **Urgency:** **Low**
3. **Category:** **Feature Request** (Integration)
4. **Sentiment:** **Positive** (highly satisfied power user, constructive suggestion)
5. **Action Recommended:**
   - Add to integration roadmap (Jira is high-priority integration target)
   - Schedule interview to understand full workflow and requirements
   - Validate demand: survey other users about Jira integration needs
   - Prioritize alongside other integration requests (Linear, Azure DevOps)
   - Consider as part of "Issue Tracking" integration initiative
   - Follow up to thank user for suggestion and share roadmap visibility
6. **Priority Score:** **6/10**

**Additional Context:**
- User Engagement: HIGH - daily usage for 3 months (power user)
- User Sentiment: Very positive, constructive feedback
- Feature Value: Workflow automation (time savings)
- Strategic Fit: Jira integration aligns with B2B SaaS PM target market
- Demand Validation: Should survey user base for interest level
- Development Scope: Medium complexity (OAuth + API integration)

