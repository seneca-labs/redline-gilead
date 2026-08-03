# Redline · Gilead enterprise deck (gilead-v1.2) · 28 slides

One deck, three questions to answer by the end: is it safe, does it scale, is it worth it.
The buyer employs the reviewers. Never say "learns your reviewers" or "predicts your reviewers." Always: "encodes the committee's standards so every agency submits to them consistently."
The AI must feel governed, optional, and auditable. Every AI claim is paired with a control.
Majority is spoken of exactly as the deck shows it: agency of record on the Feed proof, launch agency in the pilot, a row on the portfolio dashboard. Nothing more.
The deck says "Gilead" wherever the new review group would be named. When they give you the group's exact name, decide in the room whether to swap it in — it's a one-line change everywhere.
Gilead's cloud is AWS — confirmed. The Trust chapter is built on it; no cloud hedging anywhere.
Negotiation floors and red lines live in the internal pricing memo, never in this folder.

---

## 1 · Cover
Open on the mandate, not the product. "You're standing up one way to run PRC across the portfolio. This is the system that makes it stick."

## 2 · Agenda
Five stops: Problem, Solution, Redline, Trust, Investment. Trust has its own chapter now; say so plainly: "we built a whole section for the questions your security and legal teams will ask, because they should ask them."

## 3 · What we're solving
The lead line sets the enterprise frame: this is happening today at every agency submitting to your review. Seven lines, read slowly. The last row is the loop: every resubmission triggers everything above it, at every agency, independently.

## 4 · Solved, one for one
Same seven, mirrored. The reassurance beat: the process is regulatory; Redline doesn't shorten the compliance path, it changes what each step costs — and now it changes it identically at every agency.

## 5 · The solution, in three buckets
The submission, the review, the round. Bridge: "everything you're about to see is one of these three, and all of it reports up to one console."

## 6 · What Redline is (Gilead console)
The mockup is the Gilead console, not an agency tool: portfolio view, three agencies, first-pass approval, fewer malformed submissions reaching review. Point at the "Portfolio standard · Live" row: one update, live at all three agencies, same day. Read the boundary strip out loud: Redline prepares, your teams review, a named human approves, Veeva remains the system of record.

## 7 · A guided intake
The window fills itself out: the asset drops in, fields type themselves, each answer files into the rail and the next question opens. Let it run — it takes about 23 seconds and lands on the payoff card and stays there: requirements from Gilead's own history, the Aug 11 cutoff, the Aug 13 review, and the Aug 17 launch flagged as four days after review. That last row is the point: the relationship between the review date and the go-live date, known before the build starts. Don't talk over the pass; narrate the landing. This is what "fewer malformed submissions" looks like at the point of entry.

## 8 · Redline builds the deck
The canvas is the real Care For The Culture postcard page from the Feed campaign — Gilead's own program, Majority as agency of record. That's the one proof slide; it's factual, not a partnership pitch. Granularity story stays: every beat of the asset, at the granularity the committee reviews it.

## 9 · Reads it the way the committee will
Committee-standards framing only: Regulatory · Legal · Editorial · Compliance. "Likely flag," never a percentage, never a person. We don't profile reviewers; we encode the standards the committee has already expressed.

## 10 · Shows what may be flagged, and why
Every suggested change carries a source chip. Nothing is a black box. Say it plainly: it hands you corrected material with provenance, and a human approves, adjusts, or applies.

## 11 · Implement changes, with or without AI
Let the working phase breathe. The third checkbox stays open because a human hasn't decided. It doesn't guess — that line matters more in this room than anywhere.

## 12 · Track the feedback
One worklist, every source, every owner. The checklist is formatted for Veeva and pasted by a human submitter with full context, not synced.

## 13 · From sticky to answer
Drafted responses with sources. One click stages the response set for Veeva — staged, then approved, then pasted.

## 14 · Integrated in what you already use
Sources in, validated artifacts out. Only approved folders are indexed; nothing becomes a rule without a human validating it.

## 15 · Two views. One pipeline.
The centerpiece, placed here on purpose: they've now seen the whole working loop, so this is the slide that reassembles it into the enterprise shape. Left, the agency workspace: their craft, their tools, their own isolated knowledge base. Right, the Gilead console: standards and visibility. The seam is the whole product: the submission flows right, the standard flows left. Say the isolation line exactly as written: agencies never see each other's work; Gilead sees all of it.

## 16 · Review and preparation are two halves
Veeva as a whole owns review; Redline owns preparation. Falcon is deliberately NOT named on the slide — they may not be thinking about it, and we don't put a product in their head. The rows speak to what Falcon offers implicitly: routing, review, approval, the system of record. SPOKEN ONLY, and only if they raise Falcon or MLR tooling: "whatever your review runs on — including Falcon — Redline feeds it cleaner inputs. We're the other half, not a competitor." Read the landing line and stop: cleaner submissions in, faster reviews out.

## 17 · Communicates where your teams do
Calendar and inbox. Trust guardrails if asked: verified senders on approved domains, provenance on everything ingested, part-number thread matching with confirmation (never silent filing), allowlisted actions, in-app human approval for anything that exports or submits.

## 18 · The committee's standards, encoded
The Standards screen in the Gilead console. Four committees, standards counted, one live-update row. Point at the whis line: standards of the committee, never profiles of your people. Agencies see the standard, not each other.

## 19 · Built for Gilead
The training-timing argument, verbatim: "You're standing up the new review group right now. Encode the standards while the process is being defined and every agency launches into the standardized workflow on day one. Retrofit it later and you're retraining every agency twice." Four bullets, read them all; the last one is the committee's favorite: fewer malformed submissions reaching them at all.

## 20 · Redline drafts. Your people decide.
The does-it-replace-people answer. Agencies keep creative calls, the committee keeps judgment, a named human signs off, Gilead owns the standards. Nothing ships without a named human's sign-off.

## THE LIVE DEMO (no slide, run between 21 and 22 if the room wants it)
Sanitized data only. One live project, not an aggregate benchmark — that honesty is the credibility play. If the model is slow: "this step takes about a minute; that minute replaces an afternoon."

## 21 · One pipeline, every seat
Four seats, quick pass: agencies own the craft, the committee owns the judgment, Gilead owns the standard, brand marketing owns the outcome. Same people, one way of working. Bridge into Trust: "now the questions your security team is already writing down."

## 22 · Where your data lives (Trust 1)
The perimeter diagram: your AWS account, your approved model endpoints. Nothing leaves the perimeter, nothing trains a shared model, agencies are isolated, admins can inspect or delete anything. Bridge: "and here's exactly how that's wired."

## 23 · How the AI runs, inside AWS (Trust 2)
The architecture slide, left to right inside the dashed VPC: IAM + SSO in, Redline on private subnets with per-agency S3 and one KMS key each, Bedrock over PrivateLink with zero retention and zero training, staged output a named human approves — and Veeva outside the AI path entirely, because a human submits. The chips are the security team's checklist: nothing leaves the VPC, no training, cryptographic isolation, CloudTrail on every call. Land the line: AI you govern like infrastructure, not a service you send data to. If they ask which models: "the approved list on Bedrock is yours to set — that's the point."

## 24 · How the AI stays honest (Trust 3)
The third row on the mockup is the slide: no precedent found, flagged, routed to a human. Say the design requirement exactly: when it doesn't know, it flags — it never invents. Then the controls: provenance, stated confidence, staged approvals, acceptance testing run by their team.

## 25 · AI is a dial, not a default (Trust 4)
Three modes: Manual, Draft, Staged auto. The workflow is the product; the AI is a setting. Close the chapter with the landing line: use as much AI as you want — the workflow works at every setting.

## 26 · Rollout
A timeline now, read it left to right: weeks 1–8 implementation and calibration on live submissions with their team running acceptance; from week 9 the Gilead standard goes live for the franchise; then the rest of the portfolio onto the same encoded standards — the open dot, on purpose. The walk-away strip is the summary of the whole deck — read it.

## 27 · Investment
Two paths, never "POC." Path 1, Enterprise Pilot: $850K, six months, the HIV prevention franchise, three agencies with Majority as launch agency included, live submissions from day one, 50% credits on conversion. Path 2, Enterprise Platform: Year 1 $1.8–2.0M, Years 2–3 $1.2M then $1.3M, generous enterprise AI capacity sized to the portfolio (never say "unlimited"), managed operations as a visible line. Expansion strip is per-unit pricing as they grow. If ROI math comes up, do it live on a whiteboard with their numbers — there is deliberately no money slide to argue with.

## 28 · Thank you
Land the working session. Set the pilot start date in the room if the energy is there.

---

## Open TODOs
- Exact name of Gilead's new review group — deck says "Gilead" everywhere by design; swap in the group's name once confirmed, if they prefer it
- Approved Bedrock model list — ask in the room; the architecture slide is built for whatever they approve
