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
This slide advances on your clicker: four presses, one step each. Don't rush them. The order is the story: what you're submitting, what explains it, the details, then ready to build. Step one: one file, any format. The format is detected from the upload itself (PDF chip, no question asked); the asset type is the one question a human should answer, and the Flyer tile lights up asking for one confirmation. Step two: the context. Briefs, transcripts, prior rounds, PRC PDFs; drop them and Redline reads and links them. The kickoff call is context, not a memory. Step three: the details. Brand and part number typed once, and then the payoff arrives inside the same step: what this format needs, from their own history, plus the Aug 11 cutoff, the Aug 13 review, and the Aug 17 launch flagged as four days after review. No concept-or-final toggle and no round question: intake is per submission, and Redline knows from the part number's history whether this is the first round. Step four: the whole submission in one look, then Build. The relationship between the review date and the go-live date, known before the build starts. This is what "fewer malformed submissions" looks like at the point of entry.

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
Signpost first, it's on the slide now: a round starts when the committee sends comments back. This is the after-review half of the story; slides 6 to 10 were the before. Then the five nodes, left to right: comments come back, each becomes a task with a named owner, the changes get made by the agency team, each change is checked side by side with the comment it answers, and a person approves before anything goes back. The dashed return arc is the point: every round runs the same loop, and each one gets shorter, because the knowledge base and the standards compound. If follow-the-sun comes up, the spoken version: submission work runs overnight in assigned workspaces; morning means a staged queue, nothing applied, every change checked against its comment, and the agency lead approves, kicks back, or escalates.

## 14 · Prepare. Review. Approve.
Three columns, one actor each. Redline prepares. The committee reviews, in Veeva, exactly as today. Your people approve: nothing moves without a named person's sign-off, Redline never submits on its own, and the final gate stays with Gilead. That third column is the does-the-AI-decide answer; read it slowly. Falcon is deliberately NOT named on the slide. SPOKEN ONLY, and only if they raise Falcon or MLR tooling: "whatever your review runs on, including Falcon, Redline feeds it cleaner inputs. We're the other half, not a competitor."

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

## 25 · Everyone's day gets easier (OPTIONAL: hold unless the room asks)
Five seats, one benefit each, and each one makes the handoff to the next seat easier: the account lead stops hunting part numbers and sends cleaner work; the committee opens complete submissions and flags less; the creative team gets comments as clear owned tasks instead of a deck to decode; brand marketing sees status without chasing email; CPC writes guidance once and every agency follows it. The account lead row is grounded in the Aug 3 Veeva call: watched, not imagined. The landing, spoken: "Redline doesn't replace anyone. It deletes the middleware between these five seats and leaves the judgment."

---

## Appendix · for the security call (26–28)
Don't present these in the main meeting. They exist so "the appendix is built for that call" is true.

## 26 · One door out
The slide is now plain on purpose; the technical depth lives in your mouth, not on the wall. The five promises, read down: only the piece being edited (spoken, if pressed: the mask region plus padding, flattened, metadata stripped), nothing that identifies the work (never PRC comments, reviewer identities, claims language, part numbers, brand names), checked before it leaves (OCR runs on the crop before egress and blocks on ISI, claims, or identifiers), nothing is kept (per-request credentials, in-memory only, nothing at rest), every request logged (requester, asset, region, endpoint, timestamp, hashes both directions).

## 27 · How the models run. Three layers.
Premium generative editing is core product, so the model story is core trust. Layer 1, inside their environment: most of the work; spoken detail if pressed: Claude on Bedrock for text and reasoning, open-weight editing models on their own GPUs. Layer 2, a model they've already approved: spoken detail: Azure OpenAI-class on a private endpoint, no-training-by-default, customer-managed keys, zero data retention available. Layer 3, the one guarded door: the previous slide, in full. The model layer is swappable; the governance is not. Say the threat model early: no PHI; unreleased marketing materials and regulatory commentary; confidentiality and no-training, not HIPAA. The yellow chip is a real ask for this call: which outside image models are already approved, and what GPU capacity exists? Those two answers pick the default path.

## 28 · The AI lives inside your own cloud
The architecture slide, left to right inside the dashed boundary: each agency signs in to its own workspace and only its own, each agency's work stored separately under its own lock (spoken, if pressed: per-agency S3 with one KMS key each), the models inside the walls keeping nothing and learning nothing (spoken: Bedrock over PrivateLink, zero retention, zero training), the result staged until a person approves, and Veeva outside the AI path, because a person submits. Land the line: AI you govern like infrastructure, not a service you send data to. If they ask which models: "the approved list on Bedrock is yours to set; that's the point."

---

## Open TODOs
- What CPC stands for: no longer printed on a main slide; confirm before the meeting, never guess in the room
- Is Azure OpenAI approved at Gilead? What GPU capacity exists? Chip on appendix slide 27; these pick the default editing path
- Approved Bedrock model list: ask in the room; the architecture slide is built for whatever they approve
