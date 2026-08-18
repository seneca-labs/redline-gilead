# Redline · Gilead enterprise deck (gilead-v9, Nikki review build) · 24 slides + 1 optional + 3 appendix

One deck, three questions to answer by the end: is it safe, does it scale, is it worth it.
The buyer employs the reviewers. Never say "learns your reviewers" or "predicts your reviewers." Always: "encodes the committee's standards so every agency submits to them consistently."
The AI must feel governed, optional, and auditable. Every AI claim is paired with a control.
Majority is spoken of exactly as the deck shows it: agency of record on the Feed proof, launch agency in the pilot, a row on the portfolio dashboard. Nothing more.
The review group is CPC on every slide. TODO: confirm what CPC stands for before the meeting; never guess in the room.
Gilead's cloud is AWS, confirmed. The Trust chapter is built on it; no cloud hedging anywhere.
Threat model, say it early when trust comes up: there is no PHI anywhere in this system. What's inside is unreleased marketing materials and regulatory commentary. The control objective is confidentiality and no-training, not HIPAA.
Asset editing language, everywhere it comes up: "storyboard frames and illustrated assets." Never bare "assets" or "creative." Photography routes to retouchers as a precise brief.
Negotiation floors and red lines live in the internal pricing memo, never in this folder. Pricing is deliberately out of this deck; it comes separately, once the shape is agreed. Gilead is the sole contracting party; never imply agencies or vendors are invoiced.
No em dashes anywhere in this deck or these notes.

AUDIENCE: this deck is for marketing/brand and digital (Chris, Matthew). The technical depth (PrivateLink, the egress broker internals, model routing, source-checking) is a separate compliance/legal/security call. Keep the trust section confident and plain-language; offer the deep-dive call, don't give it here. The three appendix slides exist for exactly that call.

---

## 1 · Cover
Open on the mandate, not the product. "You're standardizing how PRC runs across the portfolio. This is the system that makes it stick."

## 2 · Agenda
Five stops: Problem, Solution, Redline, Trust, Rollout. Trust has its own chapter; say so plainly: "we built a whole section for the questions your security and legal teams will ask, because they should ask them." Pricing is not on the agenda on purpose; name that if asked: scope and pricing come separately, once the shape is agreed.

## 3 · What we're solving
The lead line sets the enterprise frame: this is happening today at every agency submitting to your review. Five lines, read slowly. Row 4 carries the conflict story: everyone on a different knowledge base, so feedback conflicts. Row 5 is the loop: changes re-typed into Veeva, and every resubmission starts over, at every agency, independently.

## 4 · Solved, one for one
Same five, mirrored. The reassurance beat: the process is regulatory; Redline doesn't shorten the compliance path, it changes what each step costs, and now it changes it identically at every agency.

## 5 · What Redline is (Gilead console)
The mockup is the Gilead console, not an agency tool: portfolio view, three agencies, first-pass approval, fewer malformed submissions reaching review. Point at the "Portfolio standard · Live" row: one update by CPC, live at all three agencies, same day. Read the boundary strip out loud: Redline prepares, your teams review, a named human approves, Veeva remains the system of record.

## 6 · A guided intake (arrow-keyed, 4 steps)
This slide advances on your clicker: four presses, one step each. Don't rush them. Step one is the whole intake story: two labeled drop targets, the asset in one, everything that explains it (briefs, transcripts, prior rounds, PRC PDFs) in the other. The file format is detected from the upload itself (PDF chip, no question asked); the asset type is a separate question, and the Flyer tile lights up asking for one confirmation. Form is what the file is; type is what the asset is. Two different questions, and Redline only asks the one a human should answer. The round is not asked at all: intake is per submission, and Redline knows from the part number's history whether this is the first round. Step two: the asset card types itself. Step three: the context docs, read and linked. Step four is the payoff. Hold on it: requirements from Gilead's own history, the Aug 11 cutoff, the Aug 13 review, and the Aug 17 launch flagged as four days after review. The relationship between the review date and the go-live date, known before the build starts. This is what "fewer malformed submissions" looks like at the point of entry.

## 7 · Redline builds the deck
The canvas is the real Care For The Culture postcard page from the Feed campaign: Gilead's own program, Majority as agency of record. That's the one proof slide; it's factual, not a partnership pitch. Granularity story stays: every beat of the asset, at the granularity the committee reviews it.

## 8 · Reads it the way your committee will
Committee-standards framing only: Regulatory · Legal · Editorial · Compliance. "Likely flag," never a percentage, never a person. We don't profile reviewers; we encode the standards the committee has already expressed.

## 9 · Shows what may be flagged, and why
Every suggested change carries a source chip. Nothing is a black box. Say it plainly: it hands you corrected material with provenance, and a human approves, adjusts, or applies.

## 10 · Implement changes, with or without AI
Let the working phase breathe. The third checkbox stays open because a human hasn't decided. It doesn't guess. That line matters more in this room than anywhere. Scope, verbatim: the editor edits copy, layout, graphic elements, banner families, and storyboard frames; photography routes to their retouchers as a precise brief, verified on return. The before/after came from their own March submission, produced by this exact capability. What left the building: the frame and the instruction, never review context.

## 11 · Track the feedback
One worklist, every source, every owner. The checklist is formatted for Veeva and pasted by a human submitter with full context, not synced.

## 12 · From sticky to answer
Drafted responses with sources. One click stages the response set for Veeva: staged, then approved, then pasted. Land the footer: the judgment stays, the middleware goes. That's the does-it-replace-people answer in one line; the fuller version is the optional slide 25 if the room wants it.

## 13 · One round, start to close
The five-node loop, left to right: comments land, become a worklist, the work gets done (agency or pod), a staged queue, a named human approves. Then, and only then, it moves. The dashed return arc is the point: every round runs the same loop, and each one gets shorter, because the knowledge base and the standards compound. The pod node is where offshore lives now. If follow-the-sun comes up, the spoken version: submission work runs overnight in assigned workspaces; morning means a staged queue, nothing applied, every change diffed against its request, and the agency lead approves, kicks back, or escalates.

## 14 · Prepare. Review. Approve.
Three columns, three lines each. Redline owns preparation, the committee owns review (in Veeva, exactly as today), people own approval. Falcon is deliberately NOT named on the slide. SPOKEN ONLY, and only if they raise Falcon or MLR tooling: "whatever your review runs on, including Falcon, Redline feeds it cleaner inputs. We're the other half, not a competitor."

## 15 · Three seats. One pipeline.
The centerpiece. The intro line carries the CPC context: PRC now runs across agencies, internal teams, and offshore pods; Redline is built for exactly that shape. The spoken background, if the room wants it: CPC has run this for two-plus years. Brands pushed into pilots to gauge efficiencies, submission work offshored to pods in Asia and India for cost and follow-the-sun coverage. NOT a new group. Get this right. Then the three seats left to right: agency creates and responds, never sees another agency's work; vendor pod runs submission mechanics inside an assigned workspace, no export, nothing outside scope; Gilead holds standards, status, the gate, sees everything, keeps the knowledge. The three pills are the mechanics: standards flow down, work flows up, nothing is copied. The closing argument, spoken: your knowledge stays yours; pods can change, the system remembers. Mandate path if it comes up: corporate → brand team → that brand's agencies.

## 16 · Integrated in what you already use
Sources in, validated artifacts out. Only approved folders are indexed; nothing becomes a rule without a human validating it. Veeva remains the system of record; it's the footer, read it.

## 17 · Communicates where you do
Calendar and inbox. Trust guardrails if asked: verified senders on approved domains, provenance on everything ingested, part-number thread matching with confirmation (never silent filing), allowlisted actions, in-app human approval for anything that exports or submits.

## 18 · The committee's standards, encoded
The Standards screen in the Gilead console. Four committees, standards counted, one live-update row, updated by CPC, live at three agencies. Standards of the committee, never profiles of your people. Agencies see the standard, not each other.

## 19 · Where your data lives (Trust 1)
The perimeter diagram plus six one-liners; this slide now carries the whole in-room trust story. Left to right inside the perimeter: agency workspaces, Redline, Bedrock over PrivateLink (zero retention, zero training), staged output, and Veeva outside the AI path entirely, because a person submits. The six lines answer cross-agency leakage explicitly: your AWS account and nothing else; models run inside; one audited door out with everything else network-denied; isolated workspaces with no cross-client retrieval, ever; named identities on every action; admins inspect, export, or delete anything, any time. If they want more: the appendix is built for the security call. Offer it, don't give it here.

## 20 · How the AI stays honest (Trust 2)
The third row on the mockup is the slide: no precedent found, flagged, routed to a human. Say the design requirement exactly: when it doesn't know, it flags; it never invents. Four rows: provenance on every suggestion, stated confidence, flags instead of inventions, a named human between the AI and anything that moves. The footer is the acceptance-testing promise: before go-live, CPC defines what passing looks like, and Redline is verified against live submissions.

## 21 · AI is a dial (Trust 3)
Three modes with real screens: Management (the worklist: tracking and visibility only), Reviewing (the pre-read: suggestions with sources, humans decide), Building (the deck studio: drafts and staged edits, a named human approves). The workflow is the product; the AI is a setting. Land the footer: you set the level; nothing skips approval.

## 22 · Rollout
A timeline, left to right: weeks 1–8 implementation and calibration on live submissions with their team running acceptance; from week 9 the CPC standard for the franchise; then the portfolio onto the same encoded standards. The calibration strip below is the credibility beat: no agency goes live uncalibrated; audit, calibrate, go live; the first agency's audit informs every one after it. Every agency is a completely different planet; their words will confirm it.

## 23 · What each seat gets
Four rows, two columns: what it's for, how it connects. Agencies, CPC, the committee, brand marketing. Deliberately no prices anywhere. Quick pass: agencies own the craft, the committee owns the judgment, CPC owns the standard, brand marketing owns the outcome. Same people, one way of working.

## THE LIVE DEMO (no slide, run before Next steps if the room wants it)
Sanitized data only. One live project, not an aggregate benchmark; that honesty is the credibility play. If the model is slow: "this step takes about a minute; that minute replaces an afternoon."

## 24 · Next steps
Four steps, then thank you. A security review: the appendix is built for that call. A CPC working session: how the pods run today sets the first calibration. Name the launch agency: audit, calibrate, go live. Scope and pricing: separately, once the shape is agreed. Set the working-session date in the room if the energy is there.

## 25 · The account lead's day, without the middleware (OPTIONAL: hold unless the room asks)
Grounded in the Aug 3 Veeva call; the left column was watched, not imagined: hunting part numbers from memory, stickies from scratch, knowledge walking out with staff. The landing, spoken: "Redline doesn't replace the account lead. It deletes the middleware and leaves the judgment."

---

## Appendix · for the security call (26–28)
Don't present these in the main meeting. They exist so "the appendix is built for that call" is true.

## 26 · One door out
The five enforcements, read down: payload minimization (the mask region plus padding, flattened, stripped, never the whole asset), context stripping (pixels and a short instruction, never PRC comments, reviewer identities, claims language, part numbers, brand names), outbound DLP (OCR before egress, blocked if ISI or claims or identifiers appear in the crop), ephemeral (per-request credentials, in-memory, nothing at rest), audit (requester, asset, region, endpoint, ZDR flag, timestamp, hashes both directions).

## 27 · How the models run. Three layers.
Premium generative editing is core product, so the model story is core trust. Layer 1 in-tenant: Claude on Bedrock, open-weight editing models on their GPUs. Layer 2, an endpoint they've already approved: Azure OpenAI-class, private endpoint, no-training-by-default, customer-managed keys, ZDR. Layer 3, the broker: the previous slide, in full. The model layer is swappable; the governance is not. Say the threat model early: no PHI; unreleased marketing materials and regulatory commentary; confidentiality and no-training, not HIPAA. The TODO chip is real: does Gilead have Azure OpenAI approved, and what GPU capacity exists? Those two answers pick the default path.

## 28 · How the AI runs, inside AWS
The architecture slide, left to right inside the dashed VPC: IAM + SSO in, Redline on private subnets with per-agency S3 and one KMS key each, Bedrock over PrivateLink with zero retention and zero training, staged output a named human approves, and Veeva outside the AI path, because a human submits. Land the line: AI you govern like infrastructure, not a service you send data to. If they ask which models: "the approved list on Bedrock is yours to set; that's the point."

---

## Open TODOs
- What CPC stands for: no longer printed on a main slide; confirm before the meeting, never guess in the room
- Is Azure OpenAI approved at Gilead? What GPU capacity exists? Chip on appendix slide 27; these pick the default editing path
- Approved Bedrock model list: ask in the room; the architecture slide is built for whatever they approve
