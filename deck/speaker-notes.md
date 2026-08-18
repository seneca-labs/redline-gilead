# Redline · Gilead enterprise deck (gilead-v11) · 23 slides

One deck, three questions to answer by the end: is it safe, does it scale, is it worth it.
The buyer employs the reviewers. Never say "learns your reviewers" or "predicts your reviewers." Always: "encodes the committee's standards so every agency submits to them consistently."
The AI must feel governed, optional, and auditable. Every AI claim is paired with a control.
Majority is spoken of exactly as the deck shows it: agency of record on the Feed proof and the origin slide, launch agency in the pilot, a row on the portfolio dashboard. Nothing more.
The review group is CPC on every slide. TODO: confirm what CPC stands for before the meeting; never guess in the room.
Gilead's cloud is AWS, confirmed. The Trust chapter is built on it; no cloud hedging anywhere.
Threat model, say it early when trust comes up: there is no PHI anywhere in this system. What's inside is unreleased marketing materials and regulatory commentary. The control objective is confidentiality and no-training, not HIPAA.
Asset editing language, everywhere it comes up: "storyboard frames and illustrated assets." Never bare "assets" or "creative." Photography routes to retouchers as a precise brief.
Negotiation floors and red lines live in the internal pricing memo, never in this folder. Pricing is deliberately out of this deck; it comes separately, once the shape is agreed. Gilead is the sole contracting party; never imply agencies or vendors are invoiced.
No em dashes anywhere in this deck or these notes.

AUDIENCE: this deck is for marketing/brand and digital (Chris, Matthew). The technical depth (PrivateLink, egress broker internals, model routing, source-checking) is a separate compliance/legal/security call. Keep the trust section confident and plain-language; offer the deep-dive call, don't give it here. There are no appendix slides in this build; the security material lives in your mouth and in that separate call.

---

## 1 · Cover
Open on the mandate, not the product. "You're standardizing how PRC runs across the portfolio. This is the system that makes it stick."

## 2 · Agenda
Four stops: Problem, Redline, Trust, Rollout. Trust has its own chapter; say so plainly: "we built a whole section for the questions your security and legal teams will ask, because they should ask them." Pricing is not on the agenda on purpose; name that if asked: scope and pricing come separately, once the shape is agreed. Before the first stop there's a two-minute origin story; bridge with "but first, how we got here."

## 3 · How we got here
The origin story, before the problem. Four beats, read down: The Feed, a live activation we built and run for the brand under Care For The Culture; an agent ran the day-to-day and held privacy lines it could never cross; people stayed in charge, the agent prepared and we approved everything that moved; Redline is that same discipline, pointed at PRC. Majority is the agency of record on this program; state it factually, don't pitch the partnership. Land the last line and pause: "Not a concept. A system we already run." Everything after this slide inherits its credibility from this one.

## 4 · What we're solving
The lead line sets the enterprise frame: this is happening today at every agency submitting to your review. Five lines, read slowly. Row 4 carries the conflict story: everyone on a different knowledge base, so feedback conflicts. Row 5 is the loop: changes re-typed into Veeva, and every resubmission starts over, at every agency, independently. Bridge out with the reassurance beat: the process is regulatory; Redline doesn't shorten the compliance path, it changes what each step costs, identically at every agency.

## 5 · How it works
The lead is the promise: Redline builds, reviews, and manages every PRC submission, so approval takes fewer, shorter rounds. Then the whole product in one loop, four nodes left to right: upload an asset for review (with its context, and what the committee has said before); Redline builds the submission (checked against your standards, every change staged); Gilead or an agency approves and submits (a named sign-off, every time; Redline never submits on its own); PRC reviews and the round comes back (Veeva unchanged; every comment becomes a worklist, and the system remembers). Node three is the does-the-AI-decide answer; read it slowly. Node four closes the loop; it's why the promise is true. Land the closing line: "Every round teaches the next. That's how they get fewer, and shorter." The old land line stays spoken if people-vs-AI comes up: "Redline does the preparation. Your people make every decision." Falcon is deliberately NOT named on the slide. SPOKEN ONLY, and only if they raise Falcon or MLR tooling: "whatever your review runs on, including Falcon, Redline feeds it cleaner inputs. We're the other half, not a competitor."

## 6 · The Gilead console
The mockup is the Gilead console, not an agency tool: portfolio view, three agencies, first-pass approval, fewer malformed submissions reaching review. Point at the "Portfolio standard · Live" row: one update by CPC, live at all three agencies, same day. Read the boundary strip out loud: Redline prepares, your teams review, a named human approves, Veeva remains the system of record.

## 7 · A guided intake (arrow-keyed, 4 steps)
This slide advances on your clicker: four presses, one step each. Don't rush them. The order is the story: what you're submitting, what explains it, the details, then ready to build. Step one: one file, any format. The format is detected from the upload itself (PDF chip, no question asked); the asset type is the one question a human should answer, and the Flyer tile lights up asking for one confirmation. Step two: the context. Briefs, transcripts, prior rounds, PRC PDFs; drop them and Redline reads and links them. The kickoff call is context, not a memory. Step three: the details. Brand, part number, and the launch date, typed once; then the payoff: Redline works back from the launch date and recommends the submission cutoff (Aug 11, six days out) and the PRC review (Aug 13, four days out). Nobody counts backwards on a calendar. No concept-or-final toggle and no round question: intake is per submission, and Redline knows from the part number's history whether this is the first round. Step four: the whole submission in one look, plus Redline's one-line summary of what it will build and why, drawn from the format's own history; the Build button sits on that summary card. Spoken, not printed: the whole path to launch, known before the build starts. This is what "fewer malformed submissions" looks like at the point of entry.

## 8 · Redline builds the deck
The canvas is the real Care For The Culture postcard page from the Feed campaign: Gilead's own program, Majority as agency of record. That's the proof beat; it's factual, not a partnership pitch, and it rhymes with slide 3. Granularity story stays: every beat of the asset, at the granularity the committee reviews it.

## 9 · Reads it the way your committee will
Committee-standards framing only: Regulatory · Legal · Editorial · Compliance. "Likely flag," never a percentage, never a person. We don't profile reviewers; we encode the standards the committee has already expressed.

## 10 · Shows what may be flagged, and why
Every suggested change carries a source chip. Nothing is a black box. Say it plainly: it hands you corrected material with provenance, and a human approves, adjusts, or applies.

## 11 · Implement changes, with or without AI
Let the working phase breathe. The third checkbox stays open because a human hasn't decided. It doesn't guess. That line matters more in this room than anywhere. Scope, verbatim: the editor edits copy, layout, graphic elements, banner families, and storyboard frames; photography routes to their retouchers as a precise brief, verified on return. The before/after came from their own March submission, produced by this exact capability. What left the building: the frame and the instruction, never review context.

## 12 · Track the feedback
One worklist, every source, every owner. The checklist is formatted for Veeva and pasted by a human submitter with full context, not synced.

## 13 · From sticky to answer
Drafted responses with sources. One click stages the response set for Veeva: staged, then approved, then pasted. Land the footer: the judgment stays, the middleware goes. That's the does-it-replace-people answer in one line.

## 14 · Communicates where you do
Calendar and inbox. Trust guardrails if asked: verified senders on approved domains, provenance on everything ingested, part-number thread matching with confirmation (never silent filing), allowlisted actions, in-app human approval for anything that exports or submits.

## 15 · The committee's standards, encoded
The Standards screen in the Gilead console. Four committees, standards counted, one live-update row, updated by CPC, live at three agencies. Standards of the committee, never profiles of your people. Agencies see the standard, not each other.

## 16 · Integrated in what you already use
Sources in, validated artifacts out. Only approved folders are indexed; nothing becomes a rule without a human validating it. Veeva remains the system of record; it's the footer, read it.

## 17 · The seats it serves (five cards, same format as slide 18)
Now that they've seen the whole product, name who does what. Five cards left to right, owner pills at the bottom of each card (Agency blue, Vendor pod purple, Gilead green, Redline gray): the agency, with Redline, uploads the work (makes the asset, Redline preps the submission around it in the agency's own workspace); the agency, with Redline, signs off the build (requirements arrive up front, a named lead approves every change); the vendor pod, with Redline, packages and submits (runs the mechanics, only what the agency signed off); Gilead reviews in Veeva (PRC exactly as today, CPC standards set once for every agency); all three close the round (comments become tasks, standards travel back into every workspace). Spoken background if the room wants it: CPC has run this for two-plus years; submission work offshored to pods in Asia and India for cost and follow-the-sun coverage. NOT a new group. Get this right. Mandate path if it comes up: corporate → brand team → that brand's agencies.

## 18 · Re-submission, start to close
Signpost first: a round starts when the committee sends comments back. This is the after-review half of the story; slides 7 to 11 were the before. Five nodes, left to right, each with its owner pills at the card bottom: PRC comments land, all in one place; each becomes a task with a named owner; the changes get applied by the pod, in and with Redline; agency and Gilead review each change beside the comment it answers; resubmitted to Veeva for the new round. The dashed return arc is the point: if comments come back, the same loop runs again, and each round gets shorter, because the knowledge base and the standards compound. If follow-the-sun comes up, the spoken version: submission work runs overnight in assigned workspaces; morning means a staged queue, nothing applied, every change checked against its comment, and the agency lead approves, kicks back, or escalates.

## 19 · AI is a dial (Trust 1)
Three modes with real screens: Management (the worklist: tracking and visibility only), Reviewing (the pre-read: suggestions with sources, humans decide), Building (the deck studio: drafts and staged edits, a named human approves). The workflow is the product; the AI is a setting. Land the footer: you set the level; nothing skips approval.

## 20 · How the AI stays honest (Trust 2)
The third row on the mockup is the slide: no precedent found, flagged, routed to a human. Say the design requirement exactly: when it doesn't know, it flags; it never invents. Four rows: provenance on every suggestion, stated confidence, flags instead of inventions, a named human between the AI and anything that moves. The footer is the acceptance-testing promise: before go-live, CPC defines what passing looks like, and Redline is verified against live submissions.

## 21 · Where your data lives (Trust 3)
The nested diagram carries the whole in-room trust story: your AWS account is the outer wall; inside it, the Redline environment with each agency's workspace isolated under its own lock; below, Veeva outside the AI path entirely, because a person submits. The six lines on the right answer cross-agency leakage explicitly: your AWS account and nothing else; models run inside and keep nothing; premium editing through one audited door with everything else network-denied; isolated workspaces with no cross-client retrieval, ever; named identities on every action; admins inspect, export, or delete anything, any time. Threat model early if trust questions start here: no PHI anywhere in this system. If they want more depth: offer the security deep-dive call; don't give it here.

## 22 · Rollout
A timeline, left to right: weeks 1–8 implementation and calibration on live submissions with their team running acceptance; from week 9 the CPC standard for the franchise; then the portfolio onto the same encoded standards. The calibration strip below is the credibility beat: no agency goes live uncalibrated; audit, calibrate, go live; the first agency's audit informs every one after it. Every agency is a completely different planet; their words will confirm it.

## THE LIVE DEMO (no slide, run before Next steps if the room wants it)
Sanitized data only. One live project, not an aggregate benchmark; that honesty is the credibility play. If the model is slow: "this step takes about a minute; that minute replaces an afternoon."

## 23 · Next steps
Three steps, then thank you. Follow up with CPC: a working session on how the pods run today; that sets the first calibration. Scope and pricing: sized to the shape we agree on here. A demo: live, on current or past submissions. Set the working-session date in the room if the energy is there. If security wants depth, book the separate deep-dive call; nothing in this deck depends on it.

---

## Open TODOs
- What CPC stands for: not printed on any slide; confirm before the meeting, never guess in the room
- Is Azure OpenAI approved at Gilead? What GPU capacity exists? These pick the default premium-editing path; ask on the security call
- Approved Bedrock model list: ask in the room; the data-lives slide is built for whatever they approve
