# Launch review: `for-agencies.html`

## Verdict

**STOP-SHIP. Do not send this page to a prospect yet.** The page may produce free requests, but I would budget **under 1% of qualified cold visitors becoming paid customers** in its present form, and quite plausibly zero from the first 100. The larger immediate issue is not conversion: it is the public real-business library, which creates avoidable complaint, takedown, and reputation exposure.

The basic offer is commercially plausible. The present proof is not. A buyer is being asked to believe “tailored, client-ready, overnight”; the representative output shows “fixed AI template, unverified copy, unclear rights.” Copy cannot bridge that gap.

Ranked by money at risk/opportunity:

1. **Remove the public real-name portfolio exposure.** This is a pre-outreach launch blocker.
2. **Make the representative output support the promise.** Ace currently kills the sale.
3. **Sell a bounded paid founding sprint to 30 tightly qualified agencies.** Test willingness to pay, not willingness to request free work.
4. **Replace the public free-custom-sample offer.** It optimizes the wrong conversion.
5. **Launch one credible usage plan, with white-label included and no “unlimited.”**
6. **Disclose AI directly and sell the review/accountability layer.** The current page is evasive rather than plain.

---

## 1. Legal and reputation exposure — higher priority than conversion (question 5)

### Launch gate: fail

The footer disclaimer is not sufficient. It appears on the sales page, below everything else. Each sample opens in a new tab, and a direct/search visitor never sees that footer. The sample itself then speaks as the business, publishes live contact actions, and often claims the business's copyright.

The local corpus audit found:

| Evidence | Finding | Commercial implication |
|---|---:|---|
| Top-level HTML files | 223 | 221 sample entries, plus the library index and sales page |
| Samples listed by `index.html` | **221, not 222** | “All 222” is visibly inaccurate |
| Pages with `noindex` | 27 | 196 top-level pages remain indexable |
| Pages with live `tel:` links | 209 | A visitor can treat a concept as an operational site |
| Pages saying “All rights reserved” | 186 | They appear to claim publication/copyright for the named business |
| Pages saying “Sample built by Symbio AI” | 181 | Authorship is shown; lack of commission/approval is not |
| Pages with explicit non-affiliation wording | 1 | Only the sales page has it |

Ace is the cleanest illustration: it uses a real name and phone number, states business hours and business claims in Ace's voice, and ends with “© 2026 Ace. All rights reserved.” The small “Sample built by Symbio AI” ribbon does not say Ace never commissioned, checked, or approved it.

The regulated examples are worse. `139-center-pharmacy.html` asserts licensed pharmacists, immunizations, compounding, insurance acceptance, prescription turnaround, and a history dating to 1987. There are also dental, cannabis, funeral, insurance, and government/international-mission examples. A wrong accent colour is harmless; an invented regulated service or official-sounding claim is not.

### Actual risk, in realistic order

1. **Business objection, cease-and-desist, hosting complaint, and buyer distrust: high once outreach creates exposure.** The most likely first loss is not a courtroom judgment. It is a business demanding removal, GitHub restricting content, or an agency deciding Ravi is careless with client brands. GitHub expressly treats confusing use of business names/logos as a possible trademark-policy violation and can require clarification or suspend an account in clear cases. [GitHub trademark policy](https://docs.github.com/en/site-policy/content-removal-policies/github-trademark-policy)

2. **False association / trademark claim: plausible, not automatic.** Truthfully naming a business can be nominative fair use. The problem is the presentation: official voice, branded styling, operational calls, factual assertions, and a false-looking business copyright notice. Federal law reaches likely confusion about affiliation, sponsorship, or approval. Ninth Circuit nominative-use analysis also asks whether the presentation falsely suggests sponsorship and whether more of the mark was used than necessary. [15 U.S.C. §1125(a)](https://uscode.house.gov/view.xhtml?edition=prelim&num=0&req=granuleid%3AUSC-prelim-title15-section1125), [Toyota v. Tabari](https://cdn.ca9.uscourts.gov/datastore/opinions/2010/07/08/07-55344.pdf)

3. **Copyright: conditional but material.** Twenty-eight top-level pages contain images; 27 embed image data. If any photograph, logo art, or copied prose came from a listing, social profile, or existing site, public availability is not a licence. A disclaimer cannot license it. The U.S. Copyright Office describes fair use as fact-specific, with commercial purpose one relevant factor. [Copyright Office fair-use guidance](https://www.copyright.gov/fair-use/more-info.html)

4. **Misleading factual content: lower enforcement probability, high avoidable downside.** Direct visitors can rely on invented hours, services, certifications, prices, medical capabilities, or official status. Even without a lawsuit, one screenshot sent to a named business can produce a reputational problem.

5. **Right of publicity: narrow but real for natural-person pages.** Pages named for individuals are more exposed if a person's name or likeness is used to sell Ravi's service. California's statute specifically covers knowing commercial use and provides statutory/actual remedies. [California Civil Code §3344](https://www.leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?article=3.&chapter=2.&division=4.&lawCode=CIV&part=1.&title=2.)

Full litigation is lower-probability than a complaint or takedown, but its cost is asymmetric. This is a commercial risk assessment, not a legal opinion.

### Minimum change that materially reduces the risk

**Remove the real-name library and its index from public access. Replace the proof section with 3–5 fictional/composite businesses using owned, synthetic, or properly licensed names, copy, addresses, images, and contact data.** Disable every phone, email, booking, order, donation, and form action.

Put this persistent banner on every demo, not merely in a sales-page footer:

> **Portfolio demo — fictional business. Not a live website. Names, services, prices, contact details, and claims are illustrative; calls and forms are disabled.**

Replace the proof introduction with:

> **Representative output, built to the same scope as a paid delivery. These demos use fictional businesses and licensed or synthetic assets.**

Written permission is the clean route for retaining a real business. As interim containment only, remove “All 222,” add prominent top-of-page non-affiliation notices plus `noindex,nofollow,noarchive`, remove “© [Business]” and official voice, and disable actions. That reduces discoverability and confusion; it does not cure unlicensed assets or permission issues.

---

## 2. Will it convert? No—not to paid, at a useful rate (question 1)

### Where the skeptical agency owner stops

The hero earns a click. The first proof loses it.

An agency owner will open Ace, spend 10–20 seconds, and see:

- no logo, photography, products, map, distinctive store detail, or obvious research beyond name/category/location/phone;
- Ace red applied to a generic shell;
- “What We Carry” repeated as both label and heading;
- “Visit Us Today” opening a phone call;
- unsupported claims about hours, rentals, staff expertise, local codes, and decades of trust;
- “Sample built by Symbio AI,” despite the seller being Mockup Studio/Ravi; and
- a page that looks official enough to be risky but not specific enough to win a pitch.

Opening a second standard sample makes the problem worse. **181 of the 221 indexed samples use the same “About Us / What Sets Us Apart / We'd love to hear from you” shell.** The generator itself describes its approach as a “polished, fixed HTML template” in `mockup_gen.py`. “Actual mockups, not screenshots of a template” is technically wordplay, not a persuasive distinction.

If the buyer does not inspect samples, trust breaks at pricing: “MOST POPULAR” and “Most people start on Starter” are impossible customer-behaviour claims when there have been zero customers. “Once a mockup closes a client” and “one mockup closing one client pays for the year” imply outcomes that have never happened. A new offer is acceptable; invented traction is not.

### Claims I do not believe

1. **“Full, client-ready website mockup.”** Ace is a one-page static pitch concept with unverified facts. “Client-ready” makes the agency assume QA, accuracy, brand depth, responsive testing, and safe presentation.
2. **“Ship as-is.”** The samples are not production builds: no demonstrated accessibility review, privacy/compliance work, form backend, analytics, content approval, asset licensing, or factual sign-off.
3. **“Next morning” / “most within 12 hours.”** A batch of generated pages proves generation speed, not a queue/SLA with research, QA, revisions, white-labelling, and simultaneous customers.
4. **“White-label.”** The linked output says Symbio AI, while checkout currently creates a Stripe product named “Symbio Mockups.” The page promises Ravi/Mockup Studio and agency branding; the actual customer trail does not.
5. **“222 mockups.”** The linked index contains 221. More importantly, batch volume proves generator throughput, not agency adoption or client wins.

The direct substitute is cheap. For example, Landingsite currently advertises a **$49/month agency plan with white-labelled previews and unlimited website projects**, using a 750-credit monthly pool and 25 credits for an initial homepage; it includes AI logo, images, and text. Lindo advertises a white-label agency tier at $297 monthly ($197 when billed annually) with 20 active sites. Ravi cannot win by being “another generator, delivered tomorrow.” He must win by removing the work and reputational risk that self-serve tools leave with the agency. [Landingsite agency plan](https://www.landingsite.ai/agencies), [Lindo pricing](https://lindo.ai/pricing)

### What is missing before I would reply

- The exact unit: one responsive landing page, one multi-page site, or one design direction?
- Exact inputs and output: hosted URL, downloadable source, both, and hosting duration.
- What is actually editable and by whom.
- Factual QA: who checks names, claims, hours, links, and regulated services.
- Brand QA: how agency/client logos, images, guidelines, and desired pitch angle are handled.
- Mobile/browser QA and what “responsive” means.
- Revisions, paid-plan miss/refund policy, and what consumes a credit.
- Usage rights for HTML and assets, including modification and client presentation.
- Whether Ravi ever contacts the agency's prospect. The answer should be no.
- SLA cutoff, timezone, business-day definition, queue limits, and delayed-delivery remedy.
- Exclusions: production development, ecommerce, apps, CMS, accessibility certification, legal/compliance review, analytics, hosting, and final content approval.

### Copy and order I would use

Narrow the promise to what exists and make the QA layer real before claiming it.

Replace the hero with:

> **Put a tailored website concept in tomorrow's pitch.**
>
> Send a live prospect and your agency brand. Receive one responsive, editable HTML pitch concept within two business days, with one revision included. You keep the client relationship.

Qualifier directly beneath it:

> **For agencies pitching brochure sites to local businesses. Pitch concept only—not a production build, ecommerce site, or web app.**

Replace “Actual mockups, not screenshots of a template” with:

> **Open the exact HTML deliverable.**

Add the objection the page currently avoids:

> **Why not use an AI builder myself?**
>
> You can. This service is for agencies that do not want another tool or another blank draft. Send the brief; receive an agency-branded concept that has been checked against it. If you prefer self-serve generation, this is not for you.

That answer is only defensible after a documented review step exists.

Replace the final-site FAQ with:

> **No. You receive a presentation-ready HTML concept and editable source for pitching and developer handoff. Production development, final fact approval, accessibility/compliance testing, integrations, analytics, hosting, and launch are not included.**

Remove entirely: “MOST POPULAR,” “Most people start,” “once a mockup closes a client,” “one mockup closing one client pays for the year,” and “All 222.” Do not replace zero-customer social proof with different theatre. Call it a **founding agency pilot** and earn the first case study.

Recommended order:

1. Narrow outcome-led hero.
2. Exact deliverable, exclusions, and who checks what.
3. One annotated fictional example showing input, output, turnaround, and QA performed.
4. Paid founding-sprint CTA.
5. Workflow and confidentiality/no-contact promise.
6. One launch plan.
7. Operational FAQ.
8. Two more curated fictional examples.

Do not expose the full library. More weak proof lowers conversion. Do not use Abril's richer design as the hero proof unless that quality is reproducible for every paid order; otherwise it creates expectation debt.

---

## 3. Fastest path to the first dollar (question 6)

### The single highest-EV motion this week

After the legal/proof cleanup, sell a **$99 paid founding sprint: three agency-branded pitch concepts over 14 days, one revision each, one active request at a time, delivered within two business days.** If the first concept still misses the written brief after the included revision, refund the sprint and stop.

This is not the long-term price. It is a bounded willingness-to-pay and fulfillment test that uses the existing $99 buying threshold. Do not describe a recurring Stripe link as a one-time sprint: either make the payment genuinely one-time or explicitly call it a $99 first month and disclose renewal before payment.

#### Who to contact

Build a list of **30 owners of 1–10-person US agencies/freelancers** with all three signals:

1. Their site/portfolio shows $2,000–$10,000 brochure sites for local businesses.
2. They visibly use cold outreach, free audits, speculative redesigns, or pitch demos already.
3. They have a repeated niche that matches a strong reproducible demo—restaurants/hospitality, local retail, home services, or salons.

Behaviour is the qualifier, not the word “agency.” A 50-person branding shop that wins through referrals is a worse lead than a two-person freelancer already sending website audits every week.

#### What to send

Send **one** same-niche fictional demo, not the sales page and not the public library. Show the exact input used, the interactive result, and a three-line scope card: responsive HTML, editable source, one revision. Do not attach a different custom free mockup to every message.

Send 10 hand-researched, plain-text emails per day for three days from Ravi. No automation, ads, new subscription, or generic blast is required.

#### Exact outreach copy

Subject: `A faster pitch asset for [Agency]`

> Hi [First] — I saw [Agency] builds sites for [specific niche/client]. I am testing a behind-the-scenes production service for owner-led agencies: send a live prospect and get an editable HTML pitch concept under your agency brand within two business days.
>
> This is the exact kind of deliverable: [one relevant fictional demo]. Input was [brief summary]; no builder or call is required on your side.
>
> I have capped the founding sprint at five agencies while I prove the workflow: three branded concepts over 14 days for $99 total, one revision each, no contract. If the first still misses the written brief after that revision, I refund the sprint and stop.
>
> Reply `pilot` with the first prospect and I will send the scope and Ravi Kumar/Mockup Studio payment link.

Only say “five” if Ravi actually caps and enforces five. Do not lead with AI, “222,” or subscription tiers. Disclose AI plainly in the linked scope/payment terms before purchase.

#### What to measure

| Funnel step | Minimum signal from 30 delivered emails | Diagnosis if missed |
|---|---:|---|
| Positive replies | 3 (10%) | Below this: target, proof, or message is wrong |
| Stripe payments | 1 (3.3%) | Replies but no pay: offer/proof/price is wrong |
| First drafts on time | 100% within 2 business days | Miss: SLA/capacity is wrong |
| Usable after at most one revision | 80% | Miss: product/QA is wrong |
| Used in a real pitch within 14 days | Track, no invented target yet | This establishes whether the asset fits workflow |

Also record hours spent per concept, factual corrections, and revision reasons. That determines viable pricing. **Do not generate mockup number 223 before 30 delivered messages and a diagnosed result.**

---

## 4. The free-sample offer optimizes the wrong conversion (question 2)

“Free, no card” will maximize free requests, not customers. For this offer it has four specific costs:

1. Anyone with a business name can consume bespoke work; there is no agency, pipeline, or active-prospect qualification.
2. It anchors the output at $0 immediately before offering 10 more for only $99.
3. It gives an agency usable pitch material without testing whether it values the workflow enough to pay.
4. There is no capacity cap, so successful outreach can create an overnight-service failure before revenue.

Use the paid founding sprint above. Replace every free CTA with:

> **Run a three-pitch founding sprint — $99**

Supporting line:

> **Three agency-branded HTML concepts over 14 days. One revision each. No contract. If the first still misses the written brief after revision, get the $99 back.**

If Ravi needs free work to learn, recruit at most **five hand-picked agencies privately** in exchange for a structured 20-minute feedback interview and permission to quote a truthful result. Do not make perpetual free custom work the public default.

---

## 5. Pricing and value metric (question 3)

### Current pricing is not credible as a reviewed service

| Current plan | Allowance | Maximum-use unit price | Problem |
|---|---:|---:|---|
| Starter | $99 / 10 | $9.90 | No white-label, so it cannot perform the advertised agency job |
| Pro | $249 / 40 | $6.23 | Too low to imply research, QA, branding, and revision |
| Agency | $599 / unlimited | Unbounded | Attracts the heaviest users before capacity is measured |

**$99 is not inherently too cheap for an agency AI tool; $99 for ten supposedly client-ready, overnight, reviewed outputs is too cheap to believe.** If the output remains the fixed template with unverified generated facts, raising the price will not help: self-serve competitors are cheaper and more capable. The higher price becomes credible only when Ravi sells accountable, hands-off review and delivery.

Use **pitch credits** as the value metric, defined as one responsive HTML concept for one named prospect, one design direction, and one included revision. It maps to both agency use and Ravi's workload.

- **Seats:** wrong. Seats do not drive fulfillment cost and invite credential-sharing arguments.
- **Clients won / revenue share:** wrong at launch. Wins are delayed, disputed, hard to attribute, and force the agency to disclose economics.
- **Pitch credits:** right, provided the unit and revision boundary are explicit.

White-label is table stakes on every paid agency plan, not an upsell. Differentiate later by capacity, active-request slots, turnaround, rollover, and custom-domain workflow.

### Number I would charge

After the $99 sprint, launch **one plan at $149/month for five pitch credits** ($29.80 each), including agency branding, editable source, one revision, one active request, and up to five unused credits rolling for one month. Charge **$35 per overage**. This is still inexpensive versus design labour, but it is high enough to fund a real review pass and low enough for an owner to approve without procurement.

Do not expose more tiers until fulfillment data exists. A later ladder, if demand supports it:

- **Studio: $149/month — 5 credits**
- **Pro: $349/month — 15 credits**
- **Agency: $599/month — 30 credits**

No unlimited promise until at least 90 days of observed usage, p90 delivery time, revision rate, and gross time per accepted concept are known.

### Billing/ownership gate

The important part works: `idea2_billing.py` uses purpose `ravi_product`, and `stripe_guard.py` authorizes it while keeping `symbio_agency` blocked. Do not change that separation.

The customer-facing identity does not yet match it. The Stripe product description is currently **“Symbio Mockups — [Plan]”**, and 181 standard samples advertise **“Symbio AI.”** Before any payment, use only:

> **Mockup Studio — an independent service by Ravi Kumar**

or the purchasing agency's permitted white-label on its deliverable. This is not cosmetic. A Symbio-named checkout/output muddies who owns and supplies the product and reintroduces the partnership question the purpose guard was built to avoid.

The billing command creates a real subscription link, but it does not enforce credits, queueing, revisions, cancellation state, custom domains, or entitlements. Manual fulfillment is acceptable for five founding customers; “unlimited” and a three-tier operational promise are not.

---

## 6. AI honesty: disclosure helps, evasion hurts (question 4)

The reviewed page does **not** plainly say “yes, this is AI-generated.” It says “generated” and “heavily systemised”; the linked output suddenly says “Symbio AI.” An experienced agency owner will assume AI immediately. Making them discover it in the sample feels evasive and is worse than direct disclosure.

Bare disclosure is not the sales message. The buyer does not mainly fear the letters “AI”; the buyer fears generic work, false facts, client embarrassment, unclear rights, and paying Ravi to run a tool the buyer could run in minutes.

Use this immediately, while factual review remains the agency's responsibility:

> **AI-generated, agency-controlled. We turn the brief you provide into editable HTML pitch material. Your team reviews and approves business facts before anything reaches the client.**

The stronger formulation—only after Ravi actually operates and records a QA checklist—is:

> **AI produces the first draft. Ravi checks the brief, business facts, links, mobile layout, and brand fit before delivery. You receive editable HTML under your agency branding, ready for your approval and pitch.**

Replace the secrecy-coded line “The client never sees this page” with:

> **Delivered under your agency brand, like any white-label production service. Ravi does not contact your prospect; you decide what reaches the client.**

That is honest without volunteering irrelevant production mechanics in the agency's pitch. White-label should mean a normal subcontractor relationship, not concealment of unreviewed AI output. Add written usage terms granting the agency permission to present, modify, and hand off the HTML and any included assets Ravi has the right to license; do not promise exclusive copyright over material that is not exclusively owned.

---

## The three changes required before sending this to one prospect

1. **Take the 221 real-name samples and index out of public proof; replace them with 3–5 fictional, action-disabled, properly sourced demos with persistent disclaimers.** Reason: this removes the highest-probability reputation/takedown event and stops the proof from impersonating businesses.
2. **Fix the product/proof mismatch: make one representative deliverable genuinely pitch-ready, institute factual/mobile/link QA, narrow the claim to an HTML pitch concept, define scope/revision/rights, and delete fabricated traction.** Reason: Ace currently proves the skeptic's commodity-template objection.
3. **Sell a capped $99 paid founding sprint to 30 qualified agency owners, then one $149/5-credit plan; remove public free custom work and “unlimited,” and make checkout/output identity Ravi Kumar/Mockup Studio only.** Reason: this gets a real payment signal while preserving the sole-proprietor boundary and limiting fulfillment risk.
