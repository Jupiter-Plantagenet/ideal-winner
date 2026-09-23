The criteria sit in four tiers, and they have different authority. You set tiers 1 and 2. Tier 3 is my procedure, which we can revise. Tier 4 is what this session added, and those items are my proposals until you accept them.

## 1. Hard requirements you set ([apt.md](apt.md), D016)
A programme that fails any of these is out.

1. **Time:** three years, starting now.
2. **Output:** four first-author Q1 journal acceptances before graduation, at least one in the JCR top 10%.
   - These rules are as you reported them; I haven't checked the university's regulations.
   - Still open with Kumoh: whether ESCI-indexed journals count, whether a top-10% rank in any JCR category counts, which JCR year applies, and whether conference-to-journal overlap is penalised (D028).
3. **AI is the main contribution.** Distributed systems or blockchain work with AI only in a supporting role doesn't qualify.
4. **PureChain must be substantive.** It can be concentrated in one part and needn't appear in every paper. The professor's minimum deliverable hasn't been specified yet.
5. **Resources:**
   - People: you as the main researcher, with no collaborators assumed.
   - Data and models: public data, open models, APIs and lab resources only; no private data or industry partners.
   - Money: about US$50/month for OpenRouter.
   - Hardware: 3× RTX 3090 on a shared server (24 GB each, not pooled) and your local RTX 5060 (8 GB).

## 2. Your preferences (weights and tie-breakers, not filters)
6. A slight preference for agents, used only to break ties.
7. "Frontier" means either advancing capability or making AI more reliable and useful, provided the contribution is significant.
8. A dependable core with ambitious extensions: graduation must not hinge on the riskiest part.
9. Career relevance: research scientist or engineer at a leading lab, or a startup. This informs ties but doesn't replace scientific merit.
10. Learn within the research. Current skills don't limit the choice.

## 3. Adviser procedure (D01 §7–§9)
**Gate:** reject a candidate with no plausible AI contribution, no credible data and compute path, or no coherent substantive PureChain role anywhere. PureChain is checked *after* scientific promise. An idea that fails only the PureChain test is logged, not called weak.

**Each candidate must state:**
- the precise question and what answering it would settle;
- evidence that it matters, kept separate from conjecture;
- at least three closest competitors, including the strongest simple baseline;
- what is already answered, the remaining residual, and the best argument that the residual is unimportant or already solved;
- a minimal discriminating experiment with its baseline, possible outcomes, and a continue/change/stop decision for each;
- an open-model route with a compute estimate.

**Rank on:**
- significance;
- strength of the unresolved question;
- falsifiability;
- feasible evidence;
- thesis coherence;
- publication-timing risk;
- career-relevant depth.

Each is marked strong, mixed or weak, with pairwise reasons. No multiplied probabilities, and a fatal weakness can't be averaged away. Programme A's older importance × P(truth) × P(novelty) score is superseded by this.

**Stress tests.** Does the ranking survive if:
- the learning advantage disappears;
- only one shared 24 GB GPU is available;
- API checks become unaffordable;
- one paper is rejected;
- the most exciting hypothesis turns out false?

**Feasibility:**
- Four distinct, defensible questions under one thesis idea, where the core survives if the risky extension fails.
- The PureChain study placed so the AI contribution is recognisable beyond the platform.
- Target journals verified against the institution's rules.
- GPU-hours, memory, storage and API tokens estimated.
- Planning envelope: early tests in months 1–3, then submissions around months 9–12, 15–18, 21–24 and 27–28.

**Standing rules** ([AGENTS.md](AGENTS.md), D019):
- a clear question, a strong competing explanation, and a test that could change our mind;
- simple baselines before complexity;
- evidence labelled by type;
- never protect Programme A;
- no "nobody has done X" claims drawn from a sample.

## 4. Added this session (D026–D028; my proposals until you accept them)
11. **Compare programmes, not questions.** The four-paper plan, PureChain role and compute are what decide.
12. **Kill-test before writing up:** a relevance-ordered, question-first search, full reads of the 10–15 closest papers, and an adversarial agent.
13. **"Nobody has run this experiment" is not significance.** Don't rank on it.
14. **Screen the Programme A corpus first.** The ACES competitors were already in it, unread.
15. **Plan evaluation honestly:** multi-step agent studies need interventional rollouts, not replayed cached runs.
16. **Venues:** the top-10% options in the AI category that were stable across both years are NMI, TPAMI, IEEE Transactions on Cybernetics, Information Fusion, IEEE TEVC, AI Review and IEEE TKDE. Don't plan around journals that qualified for one year only.

## Still open, and able to change the decision
- Kumoh's journal-rule interpretation.
- The professor's PureChain minimum.
- **Your niche choice:** acting-agent reliability, which fits PureChain but is crowded; D01's measurement-validity niche, which is cheaper and fits the labs but where PureChain fits poorly; or something else.

The weakest spot is the combination of criteria 3 and 4: every serious candidate so far has had either a strong AI case or a natural PureChain role, never both. I can save this as a one-page checklist in the repo if you want to score candidates against it.
