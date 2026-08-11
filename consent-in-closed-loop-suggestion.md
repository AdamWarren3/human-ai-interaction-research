# Consent Conditions for Non-Clinical Closed-Loop Suggestion Systems

**Draft v0.2** — 2026-08-08. Not submitted. Not peer reviewed.
**Type:** perspective / position piece.

---

## Abstract

Closed-loop systems that estimate a person's internal state and adapt their output
accordingly are well established in clinical neurotechnology, and a substantial
neuroethics literature addresses consent for them. That literature developed around
implanted devices, for patients with diagnosed disorders, under continuous clinical
supervision. The same architecture is now being assembled for non-invasive suggestion
delivery to healthy people, and the consent framework does not transfer intact. This
paper identifies three specific failures of transfer, argues that disclosure-based
consent is insufficient here for a reason established experimentally rather than
philosophically, proposes four structural conditions in its place, and shows that these
conditions are satisfiable to different degrees across four distinguishable contexts. It
draws its design vocabulary from an unexpected source with fifteen years of practice
behind it, and states plainly the one context it does not resolve.

---

## 1. What is being built

The relevant architecture is not speculative. A registered study at a major academic
medical centre combined standardised hypnotic susceptibility testing with
twenty-one-channel EEG, cardiac, respiratory and electrodermal measurement, together with
video and audio capture, across a ninety-minute standard hypnosis process delivered by a
trained hypnotist, to train a model estimating a subject's position on a spectrum from
anxiety through calm to trance.

That study's consent documentation is careful, and describing it precisely matters,
because it is not the problem. Participants were healthy volunteers. A trained hypnotist
and the research team were present throughout. Participants were told they would stay
aware and in control and could stop the session whenever they wished. Sensor discomfort,
transient emotional effects and the possibility of unexpected memories were disclosed.
Data use was bounded and destruction specified.

**That study instantiates supervised practice done properly, and this paper does not
argue that its consent form is deficient.**

The question is downstream. The registry description states a further aim: supporting a
closed-loop adaptive device to create optimal states using personalised content. **The
distinction between a model that measures a state and a device that produces one is where
the existing consent framework stops being sufficient** — and a device of the second kind,
once built, need not be used with a trained hypnotist in the room.

## 2. What the closed-loop consent literature already establishes

This ground is occupied. What follows extends it rather than replacing it.

Neuroethics has addressed adaptive and closed-loop systems for years, principally through
adaptive deep brain stimulation. A 2025 scoping review of closed-loop neurotechnology
covering seventy-seven references calls directly for informed consent procedures tailored
to adaptive systems, and observes that such systems can modulate neural activity in ways
that may blur the distinction between voluntary and externally driven actions — noting
that whether patients experience these interventions as an extension of their own agency
or as an external influence remains largely unexplored.

Two positions from that literature are load-bearing here.

**Consent is continuous, not a single event.** A patient with an implanted device is in
effect consenting to ongoing treatment for as long as the device remains implanted.

**Capacity can be compromised by the intervention itself.** The adaptive DBS literature
notes that loss of decision-making capacity may arise as a side effect of stimulation —
mania or impulsivity — that such effects would ordinarily be recognised at programming
visits, and asks directly whether an adaptive system offers the same checks and balances.

**That is the hardest problem in this paper, and it is already named.** Nothing below
claims otherwise.

## 3. Three failures of transfer

The existing framework was built for a configuration differing from the emerging one in
three respects, each of which changes what consent must do.

**Population.** Neuroethics addresses patients with diagnosed disorders, for whom a
therapeutic rationale, a clinical relationship and a regulatory pathway all exist. The
systems at issue here are being developed for healthy people, potentially as consumer or
wellness products, where none of the three is present.

**Supervision.** The clinical framework assumes a clinician in the loop; the programming
visit is the check the literature above relies on. A non-invasive suggestion device has
no equivalent and no structural reason to acquire one.

**Modality.** Implanted stimulation is unambiguously an external intervention;
disagreement concerns its effects on agency, not its provenance. Suggestion delivered
through content is not experienced as intervention at all. It arrives as material the
subject engages with, which makes the boundary between one's own response and an induced
one markedly less legible than in the implanted case.

## 4. Why disclosure is insufficient here

The clinical framework works to improve disclosure: better comprehension, ongoing
reconsent, clearer communication of adaptive behaviour. That is the right response when
the barrier is understanding.

**It is not the barrier here.** In a preregistered study of induced false insight,
participants warned in advance that they were about to be deceived showed no reduction in
susceptibility, and participants given a detailed explanation of the exact deception
method showed only a small reduction. The authors characterise the effect as robust and
difficult to overcome.

This is an experimental result about suggestion, not a philosophical position about
autonomy, and it constrains what a consent procedure can accomplish. **Where a mechanism
operates below the level at which warning helps, a procedure that discharges its
obligation by informing the subject has documented that they were told. It has not
protected them.**

The implication is a reduction in what consent is claimed to do. Suggestion operates
whether or not a person agreed — which is precisely why the unagreed case is a harm.
Consent is therefore not what makes a suggestion channel safe. **It is what makes
operating one permitted.** That reduction strengthens the framework, because it removes a
dependency the evidence does not support and forces the safeguarding function to be
specified rather than assumed.

## 5. Four structural conditions

| Condition | Requirement |
|---|---|
| **Limits** | Content or intensity the system will not produce, fixed before the exchange and not renegotiable within it |
| **Real exit** | A means of stopping that does not require understanding what is happening |
| **Auditable record** | An account of what was delivered, available afterwards, held where the subject can reach it |
| **Authored target** | The subject specified the objective rather than agreeing to one proposed to them |

Two require comment.

**Real exit** is stated this way because an exit requiring situational awareness is not an
exit for a subject whose situational awareness is under modification. Recall of a
pre-agreed token places a lower cognitive demand than assessment of one's own state.

**Limits fixed outside the exchange** is stated this way because a limit set during an
exchange is renegotiable by the process it constrains.

## 6. Four contexts

These conditions are not uniformly satisfiable, and a framework ignoring that will either
prohibit legitimate use or license unsafe use.

**Ambient.** Recommendation feeds, rankings, autoplay. No request is made and no consent
is available — there is no moment at which it could be given. What is owed is disclosure
and exit, and the exit must not require noticing that shaping is occurring.

**Requested, ordinary.** A subject asks for something specific. Consent is per-request and
revocable by ending the exchange. No additional apparatus is required.

**Requested, high-intensity, self-directed.** A subject seeks sustained engagement and sets
terms in advance. The conditions are partly satisfiable. See Section 8.

**Requested, high-intensity, supervised.** A qualified third party is present. **This is
the only context in which all four conditions are met by something other than the
subject's own vigilance** — limits held externally, exit available to a second party,
record kept by someone other than the system, target witnessed.

The argument for supervision is therefore not that it permits more. It is that it is the
only arrangement in which the conditions are satisfiable at all — a recapitulation, in a
non-clinical setting, of what the programming visit was doing in the clinical one.

## 7. A tested vocabulary from an unexpected source

The design requirements above have been worked on for roughly fifteen years by a
community the ethics literature has not consulted.

Nordic live action role-play developed formalised safety mechanics for immersive
experience: a signal halting everything immediately; a distinct signal reducing intensity
without ending; content designated as never appearing; content designated as occurring
off-screen; and structured mid-experience renegotiation. The distinction between halting
and reducing is load-bearing — without the second, a participant who wants less has only
the option of ending, and may take neither.

That tradition also produced its own critique, anticipating Section 4 from practice rather
than experiment: a stop signal used as the only mechanism **places responsibility for
recognising harm on the participant experiencing it**, and where a setting is designed to
test limits, the initiator may continue until told to stop. The response was not to
abandon intense practice but to refuse single-mechanism designs — layered tools, a
facilitator, structured debriefing.

**This is the organising principle proposed here.** What separates a defensible
arrangement from an indefensible one is not the intensity permitted but how many
independent mechanisms remain when one fails — and the first to fail is always the one
depending on the subject noticing.

## 8. The case this does not resolve

Every mechanism in Section 7 assumes co-participants, a facilitator and a debrief. A
subject alone with a system has none. The only counterpart is the system, which is also
the party the limits are set against, and there is no second observer.

**A self-directed high-intensity context can be made better than nothing and cannot be
made adequate by any arrangement described here.** Pre-agreed limits, an out-of-band stop,
a distinct intensity control and a retrievable record each improve on their absence. None
supplies an independent observer, and Section 4 indicates the subject is the party least
able to serve as one.

This mirrors the unresolved question in the clinical literature — whether an adaptive
system offers the checks a programming visit provided — with one difference. In the
clinical case a clinician exists and the question is whether the device bypasses them. In
the non-clinical case **there was never a clinician to bypass.**

**And this is the paper's sharpest observation about current deployment.** The
configuration just described — fully equipped and still inadequate — is better resourced
than the ordinary case. Most people interacting at length with adaptive systems have no
pre-agreed limits, no stop distinct from quitting, no intensity control and no retrievable
record. The inadequacy of the best-equipped self-directed arrangement is a statement about
what is already deployed with none of it.

## 9. Limitations

**No empirical claim is made.** This is an argument from the structure of arrangements. No
study compares consent procedures across these contexts, and the four conditions are
proposed, not validated.

**The threshold for supervision is unspecified**, deliberately. Who qualifies as a third
party, and for which subjects supervision should be required, are regulatory and
professional questions outside a structural argument.

**Detecting unfitness to proceed is unsolved**, here and in the clinical literature. The
framework is constructed so that the supervised context does not depend on such a test.
The self-directed context has no comparable resource, which is the substance of Section 8.

**The role-play material is practitioner literature**, not controlled study. It is offered
as a source of tested design constraints and vocabulary, not as evidence.

---

## Citation status

**Verified 2026-08-08 from primary source:** the medical-centre study's informed consent
documentation and registry description; the 2025 closed-loop neurotechnology scoping
review; the adaptive DBS consent literature quoted in Section 2; the preregistered warning
study in Section 4; the role-play safety mechanics and their internal critique in Section
7.

**Required before submission:** full references in the target venue's format; confirmation
of the registered study's final status; and **a systematic rather than targeted search of
the neuroethics literature** — Section 2 rests on a targeted one, and this paper's central
claim is that a specific extension has not yet been made, which cannot be asserted on the
strength of a handful of queries.
