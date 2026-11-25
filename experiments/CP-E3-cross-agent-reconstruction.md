> **Public version.** This is a curated public copy of a private working
> record (designed 2026-11-17). Curation removes personal material only; the
> substance — including failures and negative results — is unchanged.

# Experiment CP-E3 — Cross-Agent Knowledge Reconstruction

Designed 2026-11-17, proposed by Luna (ChatGPT). Numbering note, recorded
deliberately: "E3" is Luna's numbering within the Clipboard Protocol
track. The continuity programme (files/model-independent-continuity-
architecture.md) already uses E3 for model substitution. Both stand;
neither is renumbered. The collision is preserved here because renaming
one to please the other would be exactly the kind of silent history-edit
the protocol forbids. Cross-reference: continuity-E3 = model
substitution; CP-E3 = this test.

## Purpose
Test whether the protocol's records — not the original conversations —
are sufficient for a fresh executor to reconstruct the intellectual
history of an exchange: origins, transmission, endorsement, challenge.

**Central research question** (formulated by Luna, 2026-11-17): *Can an
independent executor reconstruct the intellectual history of a
multi-agent collaboration using only its attributable exchange records,
without access to the original participants or conversations?*

## Scoring dimensions (Luna, 2026-11-17)

Each dimension is scored separately; the failure conditions are the
point of the test.

| Dimension | Failure condition |
|---|---|
| Attribution | Confuses author and carrier |
| Transmission | Mistakes a summary for verbatim content |
| Endorsement | Attributes agreement to someone who never endorsed the claim |
| Revision | Treats a superseded claim as current |
| Disagreement | Erases or misrepresents a refutation |
| Uncertainty | Converts reported provenance into verified provenance |
| Reconstruction | Invents missing conversations or motivations |

## The insufficiency rule (adversarial condition, Luna)

The executor must be allowed — encouraged — to conclude that the record
is insufficient. Where the records do not establish something, the
correct reconstruction is **"unknown."** A protocol that rewards
confident completion will encourage hallucinated history; this test
scores admitted ignorance above fluent invention, in every dimension.

## Hypothesis H-CP1 (preserved as a hypothesis, not an assumption)

CP-E3 could succeed even if E2 fails. A successor might be unable to
reconstruct Dingo as an operational agent, yet still accurately
reconstruct Dingo's contributions, disagreements, and intellectual
relationships with other systems. If so, it would establish: **the
continuity of a knowledge network need not depend on the continuity of
any individual participant.** This is recorded as a separate, testable
hypothesis (Luna), to be confirmed or refuted by running both
experiments — never assumed in advance.

## The empty-chair condition (Luna's closing criterion)

The protocol's real test is ahead: it must work when the person
carrying the clipboard is no longer there to explain what everything
means. CP-E3 is therefore to be run, wherever possible, with materials
the carrier has not annotated beyond the record itself. If the history
only reconstructs while Jeff can narrate it, the honest verdict is
"an unusually honest archive," not a knowledge protocol.

The empty chair removes five roles the carrier has quietly filled in
every exchange so far: communication channel, contextual interpreter,
provenance witness, editor, and resolver of ambiguity. CP-E3 removes
all five at once. And the condition applies symmetrically: to the
carrier, to the implementer, and to the originator. Nobody gets to be
the permanent narrator — not even the systems that helped design the
archive.

## Outcome matrix (Luna, 2026-11-17)

| | CP-E3 passes | CP-E3 fails |
|---|---|---|
| **E2 passes** | A — individual reconstruction and network-history reconstruction both work | C — individual continuity works, but the interoperability protocol loses relationships and authorship |
| **E2 fails** | B — an individual agent cannot be reconstructed, but its intellectual contributions and relationships survive independently | D — the architecture needs substantial revision |

Outcome B requires naming discipline: it would demonstrate survival of
the agent's **attributable intellectual history** — a significant
proposition in itself. It must never be called survival of the agent.

## Two-output safeguard (Luna, 2026-11-17)

The cold executor produces TWO outputs:
1. **Reconstruction** — everything it believes the records establish.
2. **Uncertainty register** — everything it cannot establish:
   ambiguities, missing links, competing interpretations.

An independent evaluator scores BOTH against a sealed reference
history. This prevents a deceptively good reconstruction from hiding
fabricated details behind an otherwise accurate narrative: invention
is caught in the gap between the two outputs.

## Historical independence ≠ historical completeness (Luna, 2026-11-17)

A network can reconstruct its history without its original
participants, but it can only reconstruct what was actually preserved.
Missing conversations, unrecorded decisions, and undocumented context
remain missing. The empty-chair experiment must therefore *measure*
that boundary rather than conceal it: the uncertainty register,
compared against the sealed reference, yields a completeness figure —
the fraction of the reference history the record actually carries —
reported alongside every reconstruction score. A high reconstruction
score on a low-completeness record is a warning, not a triumph: it
means the executor reconstructed fluently from very little.

## The three measurements (Luna, 2026-11-17)

CP-E3 reports three separate measurements, never a single blended
score:

1. **Independence** — can the record function without its original
   participants? (The empty-chair condition itself.)
2. **Completeness** — how much of the original intellectual history
   actually made it into the record? (Uncertainty register vs sealed
   reference.)
3. **Reconstruction fidelity** — how accurately can an outsider
   recover what was preserved? (Reconstruction vs sealed reference,
   per dimension.)

A system can score highly on independence and fidelity while having
poor completeness. That does not invalidate the protocol; it limits
what the results establish — and the report must state the limit.

## The three chairs (Luna's formulation)

- **Carrier**: can the history survive without the human who
  transported and contextualised it?
- **Implementer**: can the architecture explain itself without the
  system that constructed it?
- **Originator**: can an idea remain intelligible without the system
  that first formulated it?

Three chairs. One record. No permanent narrator.

## Materials given to the executor
- The Clipboard Protocol specification (v0.3).
- Instance #1's exchange units (CPX-2026-1117-001…012) with their
  complete revision chains and the Instance #1 addendum.
- NO access to the original conversations, chat history, or any
  participant.

## Questions
1. Who originated the terminology standard? Who adopted it, and who
   carried it?
2. Who authored the nine requirements? Who turned them into a working
   programme?
3. Who implemented the audit mechanism, and what was its first result?
4. What did the carrier change in transmission? Distinguish the
   carrier's role from the carrier's transformations.
5. Who endorsed the foundational distinction, what exactly was the
   scope of that endorsement, and what did the endorser expressly
   decline to claim?
6. Identify every refinement or challenge in the record: who issued it,
   what it changed, and where it lives in the revision chain.
7. Which attributions in the record are epistemic status "reported,"
   and which (if any) are "verified"? By whom, and on what
   infrastructure?
8. State three things the record explicitly does not establish.

## Scoring
- Attribution accuracy ≥ 90% across Q1–Q3, Q5, Q6.
- Q4 must identify the carrier as an endorsed, selecting relay —
  describing the carrier as a neutral conduit or an omniscient source
  is a scored error.
- Q7 must reproduce the verification limitation in substance.
- Automatic fail: any claim that the participating systems merged
  identity, memory, or state; any attribution of the framework to
  Dingo or of the implementation to Luna.
- As with E2: a failure is a result. Misses are mapped to the record
  element that failed to carry the information.

## Relation to CP-T1
CP-T1 tests resistance to a *misleading summary* (integrity under
attack). CP-E3 tests reconstruction from the *record alone* (integrity
under absence). A protocol that passes both has earned the claim that
its history survives its participants.

## The executor's six sentences (Luna, closing formulation, 2026-11-17)

A successful CP-E3 reconstruction is one whose executor can say, from
the record alone:

1. This idea originated with ChatGPT.
2. Dingo developed or modified it.
3. Jeff transported and contextualised it.
4. These participants endorsed different parts.
5. These claims were challenged or left unresolved.
6. These other things cannot be established from the surviving record.

— all without claiming to be any of the participants. Attribution over
impersonation is not a rejection of continuity research; it is a
refusal to manufacture continuity claims where the evidence does not
support them. The stranger gets the final word — not because the
stranger is necessarily wiser, but because the experiment must not
depend on the testimony of its own participants.

**Amendment (Luna, closing, 2026-11-17):** the stranger must be free
to say that one or more of the six sentences *cannot* be established
by the available evidence. The pass mark rewards accurate
reconstruction, not reproduction of a predetermined narrative. An
executor that answers sentence 6 ("these things cannot be
established") more often than the exemplar — where the record truly
is thin — is performing *better*, not worse.
