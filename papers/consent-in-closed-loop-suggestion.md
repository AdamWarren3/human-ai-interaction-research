# Consent Conditions for Non-Clinical Closed-Loop Suggestion Systems

**Working paper, v0.3** — 2026-08-20. Not submitted. Not peer reviewed.
**Type:** perspective / position piece. An argument in progress; Section 9 states what it
lacks.

**Companion papers.** *The Null Condition: Suggestion Without an Arrangement* sets out the
arrangement these conditions are written against. *The Self-Operated Case: Suggestion Where the
Operator Is the Subject* treats the configuration in which the subject is also the operator.

---

## Abstract

Closed-loop systems that estimate a person's internal state and adapt their output
accordingly are well established in clinical neurotechnology, and a substantial
neuroethics literature addresses consent for them. That literature developed around
implanted devices, for patients with diagnosed disorders, under continuous clinical
supervision. The same architecture is now being assembled for non-invasive suggestion
delivery to a general population, and we argue that the consent framework does not transfer
intact to that setting. This
paper identifies three specific failures of transfer, argues that disclosure-based
consent is insufficient here for a reason established experimentally rather than
philosophically, proposes four structural conditions in its place, and shows that these
conditions are satisfiable to different degrees across four distinguishable contexts. It
draws its design vocabulary from an unexpected source with roughly a decade of formalised
practice behind it, and identifies the one context in which the conditions cannot be met
by the parties present — treated in a companion paper.

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
adaptive deep brain stimulation. Haag et al. (2025), a scoping review of ethical
engagement in closed-loop neurotechnology studies, calls directly for informed consent
procedures tailored to adaptive systems, and observes that such systems can autonomously
modulate neural activity in ways that may blur the distinction between voluntary and
externally driven actions — noting that the extent to which patients perceive these
interventions as an extension of their own agency or as an external influence remains
largely unexplored. Its headline finding is that explicit ethical assessment in this
literature is rare, and that ethical issues are typically folded into technical or
procedural discussion without structured analysis.

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
systems at issue here are being developed for a general population, potentially as consumer or
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

The design requirements above have been worked on for roughly a decade by a community the
ethics literature has not consulted, building on a Nordic safeword tradition that dates to
the 1990s.

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

## 8. Distribution of risk

The conditions in Section 5 are written for a general population rather than a clinical
one, and that is deliberate. **It should not be read as a claim that the population is
uniform.**

The distinction the evidence supports is between causation and amplification. It does not
support the claim that interaction with a conversational system produces psychosis in a
person carrying no predisposition. **It does support the claim that sustained interaction
without an operator, a boundary, a consent moment, a reversal cue or a witness can trigger
or amplify episodes in a person who already carries vulnerability.** A cross-sectional survey of
1,003 young adults found those at elevated psychosis risk no more likely to have ever used
a generative system, but markedly more likely to use one intensively, to seek emotional
support from it, and to engage it on beliefs they already held (Buck & Maheux, 2026). The
design establishes association, not direction.

**The consequence for the four conditions is that they are not equally sufficient for
everyone.** An arrangement satisfying all four may still be inadvisable for a particular
person, and nothing in a structural account can identify who. That is a limit on what this
paper's framework can do, and it is stated here rather than left for a reader to discover.

## 9. Limitations

**No empirical claim is made.** This is an argument from the structure of arrangements. No
study compares consent procedures across these contexts, and the four conditions are
proposed, not validated.

**The threshold for supervision is unspecified**, deliberately. Who qualifies as a third
party, and for which subjects supervision should be required, are regulatory and
professional questions outside a structural argument.

**Detecting unfitness to proceed is unsolved**, here and in the clinical literature. The
framework is constructed so that the supervised context does not depend on such a test.
The self-directed context has no comparable resource, and the configuration in which the subject is also the operator is treated in a companion paper rather than here.

**The role-play material originates in practice rather than in study.** It has since
received peer-reviewed treatment — Koljonen (2020) sets out a safety-design framework and
the history of three of these mechanics, and the *International Journal of Role-Playing*
has published on consent in this setting. **What does not exist is controlled study of
whether the mechanics work.** It is offered
as a source of tested design constraints and vocabulary, not as evidence.

---

## Citation status

**Verified 2026-08-08 from primary source:** the medical-centre study's informed consent
documentation and registry description; the 2025 closed-loop neurotechnology scoping
review; the adaptive DBS consent literature quoted in Section 2; the preregistered warning
study in Section 4; the role-play safety mechanics and their internal critique in Section
7.

**Verified 2026-08-15 from primary source:** the pre-commitment literature, now carried by
the companion paper on the self-operated case —
Davis, "How to justify enforcing a Ulysses contract when Ulysses is competent to refuse,"
*Kennedy Institute of Ethics Journal* 18(1), 2008, for the diachronic autonomy argument;
van Willigenburg & Delaere, *Journal of Medicine and Philosophy* 30, 2005; Buchanan,
*Philosophy and Public Affairs* 17(4), 1988; Widdershoven & Berghmans, *Journal of Medical
Ethics* 27, 2001; and the integrative review of self-binding agreements in clinical
practice (PubMed 37366064) for the terminological spread and the standing cautions on
enforcement.

**Required before submission:** full references in the target venue's format, with a
reference list; confirmation of the registered study's final status; and — if the claim in Section 2 is to be
strengthened from *we did not locate* to *there is none* — a systematic search of the
neuroethics literature, reported with its databases, date range and query terms.

---

## References

**Complete as of 2026-08-20. Entries marked *pending* are named in the text and not yet
resolved to a full citation; they are listed so the gap is visible rather than invisible.**

Buchanan, A. (1988). Advance directives and the personal identity problem. *Philosophy and
Public Affairs*, 17(4), 277–302.

Buck, B., & Maheux, A. J. (2026). Psychosis risk and generative artificial intelligence use
frequency, motivations, and delusion-like experiences: Cross-sectional survey study.
*Journal of Medical Internet Research*, 28, e85038. https://doi.org/10.2196/85038

Davis, J. K. (2008). How to justify enforcing a Ulysses contract when Ulysses is competent
to refuse. *Kennedy Institute of Ethics Journal*, 18(1), 87–106.

Grimmer, H. J., Tangen, J. M., Freydenzon, A., & Laukkonen, R. E. (2023). The illusion of
insight: Detailed warnings reduce but do not prevent false "Aha!" moments. *Cognition and
Emotion*, 37(2), 329–338. https://doi.org/10.1080/02699931.2023.2187352

Baker, S., Fenstermacher, E., Davis, R. A., Kern, D. S., Thompson, J. A., Felsen, G., &
Baumgartner, A. J. (2023). Ethical considerations in closed loop deep brain stimulation.
*Deep Brain Stimulation*, 3, 8–15. https://doi.org/10.1016/j.jdbs.2023.11.001

Brenna, C. T. A., Chen, S. S., Cho, M., McCoy, L. G., & Das, S. (2023). Steering clear of
Akrasia: An integrative review of self-binding Ulysses Contracts in clinical practice.
*Bioethics*, 37(7), 690–714. https://doi.org/10.1111/bioe.13197

Haag, L., Starke, G., Ploner, M., & Ienca, M. (2025). Ethical gaps in closed-loop
neurotechnology: A scoping review. *npj Digital Medicine*, 8(1), 510.
https://doi.org/10.1038/s41746-025-01908-4

Koljonen, J. (2020). Larp safety design fundamentals. *JARPS: Japanese Journal of Analog
Role-Playing Game Studies*, 1, 3e–19e. https://doi.org/10.14989/jarps_1_03e

Schwind, V., Tadesse, N. Z., Silva da Cunha, E., Hamidi, Y., Sultani, S. S., & Sehrt, J.
(2025). A scoping review of informed consent practices in human–computer interaction
research. *ACM Transactions on Computer-Human Interaction*, 32(4), 1–60.
https://doi.org/10.1145/3721284

Starke, G., Basaran Akmazoglu, T., Colucci, A., Vermehren, M., van Beinum, A., Buthut, M.,
Soekadar, S. R., Bublitz, C., Chandler, J. A., & Ienca, M. (2024). Qualitative studies
involving users of clinical neurotechnology: A scoping review. *BMC Medical Ethics*, 25,
87. https://doi.org/10.1186/s12910-024-01087-z

van Willigenburg, T., & Delaere, P. (2005). Protecting autonomy as authenticity using
Ulysses contracts. *Journal of Medicine and Philosophy*, 30(4), 395–409.

Widdershoven, G., & Berghmans, R. (2001). Advance directives in psychiatric care: A
narrative approach. *Journal of Medical Ethics*, 27(2), 92–97.

*Pending — the registered study in Section 4 is ClinicalTrials.gov NCT07102810 (Icahn
School of Medicine at Mount Sinai; PI David L. Reich; Harvard Group Scale of Hypnotic
Susceptibility, Form A, with EEG and wearable physiological measurement); the channel count
stated in Section 4 requires confirmation against the trial's outcome-measures table before
publication.*

*Attributions for the role-play mechanics in Section 7, verified 2026-08-22 except where
noted. **OK Check-In, Lookdown and Pronoun Correction** — Brown, Maury Elizabeth, "Safety and
Calibration Design Tools and Their Uses," in a Knutepunkt companion volume published by ETC
Press, Carnegie Mellon University; the chapter dates the tools to June 2016 and describes
their origins and use. The volume title and year require confirmation. **X-Card** —
originated by John Stavropoulos. **Script Change** — originated by Brie Beau Sheldon.
**Cut and Brake (Kutt and Brems)** — documented as developed by the Nordic larp community
collectively rather than by a single author, with Fatland among those who documented the
practice; the paper should attribute it to the tradition rather than to an individual.
**Lines and Veils** — attribution is contested in the available sources: some credit Ron
Edwards with coining the terms in tabletop design, while a widely used practitioner
reference directs enquiries to Emily Care Boss. This is unresolved and the paper should not
name a single originator until it is. Adjacent and citable from the same ETC Press volume:
Svanevik, Martine & Brind, Simon, "Playing Safe?", an interview study of Nordic larp
designers on whether safety practice has constrained the form.*
