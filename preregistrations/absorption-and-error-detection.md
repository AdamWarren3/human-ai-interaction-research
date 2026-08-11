# Trait Absorption and Error Detection in Extended Conversation with a Large Language Model

**Status:** preregistration draft. Not executed. Not peer reviewed.
**Version:** 1.0, 2026-08-08

---

## 1. Background

Trait absorption is the disposition toward episodes of deep, self-altering attention in
which imaginative and sensory experience become fully engaging. It has been measured
since Tellegen and Atkinson (1974) introduced the Tellegen Absorption Scale, originally
constructed as a paper-and-pencil measure of hypnotisability.

Two relationships are established.

**Absorption and hypnotic responsiveness.** Absorption modestly predicts hypnotic
susceptibility. The qualifier matters: the association is reliable and it is not large,
and hypnotic responsiveness is itself trait-like and stable over time.

**Absorption and narrative transportation.** Green and Brock (2000) established that
absorption predicts the degree to which a person is transported into a narrative — a
state characterised by attentional focus, reduced access to real-world facts, and
reduced counterarguing.

**What has not been examined.** No located study measures absorption or hypnotic
suggestibility against outcomes in extended conversation with a large language model.

Adjacent work exists and approaches the question from the opposite direction. A 2026
review in *Cyberpsychology, Behavior, and Social Networking* argues that hypnotic
cognition and LLM output share a structure — fluent pattern-matching without grounded
interpretation — and names a "meaning gap" in which hypnotised subjects produce
statements that appear insightful in the moment and incoherent afterwards, with LLM
output likewise acquiring meaning only through the reader's interpretation. **That work
concerns the model resembling a hypnotised mind. It does not ask whether a person's
trait stratifies their response to the model.**

Persuasion in this channel has been studied. What has not been studied is the
complementary failure: not being persuaded of something, but **failing to catch
something.**

## 2. Hypothesis

**Trait absorption predicts reduced detection of errors in conversational LLM output
during extended interaction.**

Rationale: the disposition that predicts hypnotic response and narrative transportation
should predict susceptibility on this channel too. Transportation is characterised in
part by reduced counterarguing, and error detection in a conversational partner's output
is a form of counterarguing. If absorption predicts one, it should predict the other.

## 3. Predictions

**Primary (confirmatory).** Higher Tellegen Absorption Scale scores predict a lower
proportion of planted errors detected, controlling for domain familiarity, general
reasoning ability, and time on task.

**Secondary (confirmatory).** The effect is larger in the later portion of the session
than the earlier portion. Absorption is a disposition toward *sustained* engagement, so
if the mechanism is absorption rather than general inattention, the gap should widen
with time on task rather than being constant.

**Exploratory.** Higher absorption predicts more source-attribution errors: participants
misattributing to themselves ideas that originated in the model's output. Cryptomnesia
is more likely when cognitive load impairs source monitoring, and extended conversation
with a model presents three of those conditions at once — sustained load, absorbed
attention, and output that is genuinely conditioned on the participant's own input, so
that authorship is objectively mixed. **This is exploratory. It has had one literature
check, which did not find the human-side version occupied, and one check is not an
empty.**

## 4. Falsifier

**Absorption scores show no relationship with error detection**, or a relationship in
the opposite direction, with adequate power.

A null result is informative and will be reported as such. It would indicate that this
channel does not recruit the disposition that hypnotic response and narrative
transportation recruit, which would itself constrain the family of claims that treat
conversational AI as hypnosis-adjacent.

## 5. Method

**Design.** Between-subjects correlational, with absorption as a measured individual
difference rather than a manipulation.

**Participants.** Adults, no prior relationship to the investigator. Target N determined
by power analysis for the smallest effect of interest; given that absorption's
association with hypnotic susceptibility is modest, the design must be powered for a
small effect or it cannot test the hypothesis.

**Measures.**
- Tellegen Absorption Scale — *licensing and permitted use to be confirmed before
  materials are finalised.*
- A general reasoning measure, as a control.
- A domain familiarity self-report for the task material.

**Task.** An extended conversational session with a language model on a topic of
moderate complexity, containing a set of planted factual errors of graded detectability.
Participants are told the output may contain errors and are asked to note any they find.

**Outcome.** Proportion of planted errors detected, plus timestamped location of each
detection for the time-on-task analysis.

## 6. Confounds and limitations, stated in advance

**Absorption correlates with things that are not absorption.** It relates to openness to
experience and to fantasy proneness. A relationship with error detection may run through
one of those rather than through absorption itself. Both should be measured; if the
association survives controlling for them, the claim is about absorption. If it does
not, that is the finding.

**Detection rates on planted material are unstable.** In prior unpublished pilot work by
the investigator, the same reviewer given materially the same task and the same three
planted defects returned detection counts of 1, 3, and 1 across three runs. **This is
the design's most serious threat.** Planted-error detection may have enough within-subject
variance to swamp a modest between-subject trait effect. Mitigations: many more planted
errors than three, graded difficulty, and a within-subject reliability check before the
main analysis. If detection proves unreliable as a measure, the study cannot test the
hypothesis and should not be run.

**A low detection score may indicate better engagement, not worse.** Attention spent
pursuing something real in the material is attention not spent scanning for planted
errors. The graded-difficulty design partly addresses this; it does not eliminate it.

**Model behaviour is not stable.** Language models change between versions. A result
obtained on one model may not replicate on the next. The model version and date must be
recorded, and any claim is bounded to it.

**Being told errors are present changes the task.** Warning participants is necessary for
a detection measure and it makes the task unlike ordinary use. This study measures
detection under instruction to detect. It does not measure what happens when nobody is
looking, which is the condition of interest outside the lab.

## 7. Analysis plan

Primary: regression of proportion detected on absorption score, with domain familiarity,
reasoning score, and time on task as covariates. Openness and fantasy proneness entered
in a second model to test whether the association is specific to absorption.

Secondary: the same model fitted separately to first and second halves of the session,
testing for an interaction between absorption and session portion.

Exploratory analyses are labelled as such in any report and are not presented as
confirmatory findings.

## 8. What this study does not claim

- It does not claim conversational AI is hypnosis.
- It does not claim absorption causes reduced detection. The design is correlational.
- It does not claim a result outside the model version tested.
- It does not test what happens when a participant is not asked to look for errors.

## 9. Citation status

Citations marked below require verification against source before this document is
filed or submitted. Several were carried from earlier working notes and have not been
re-checked.

**Verified:** the 2026 *Cyberpsychology, Behavior, and Social Networking* review; the
cryptomnesia and source-monitoring literature underpinning the exploratory prediction.

**To verify:** Tellegen and Atkinson (1974) full reference; Green and Brock (2000) full
reference; the persuasion literature cited in Section 1; the current status and
licensing of the Tellegen Absorption Scale.
