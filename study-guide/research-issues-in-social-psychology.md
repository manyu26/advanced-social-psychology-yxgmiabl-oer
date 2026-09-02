# Module 2: Research Issues in Social Psychology

::: info
**Reference:** Giner-Sorolla, R. (2025). *Changing practices and priorities in social psychological research methods and reporting.* In *The Handbook of Social Psychology* (6th ed.), Situational Press (CC BY-NC-ND 4.0). https://doi.org/10.70400/ZUTF8520
**Audience:** master's-level students in a graduate seminar
**Package license:** CC-BY-SA-4.0
**Note:** slug `research-issues`; Module 2 of Unit 1. Facts and findings are drawn from the anchor chapter; all prose here is original. The Open Science Collaboration (2015) and Chester & Lasko (2021) readings are assigned and cited, but are not open sources and are not drawn from.
:::

::: success
**Module Learning Objectives**

- Describe the publication and reporting system as it stood around 2010, and explain the evaluative norms researchers were meeting.
- Explain why a single 2011 paper destabilized confidence in the field's rules of evidence.
- State each of the eight proposed evidence solutions, the problem it targets, and its principal cost.
- Explain why theory quality and method quality are the same problem seen twice.
- Describe what a manipulation check can and cannot establish.
- Explain the structural mechanisms behind generalizability bias, and why WEIRD is more than a sampling footnote.
- Evaluate empirical claims without collapsing into either complacency or blanket distrust.
- Distinguish exploratory from confirmatory questions and analyses, and explain what a pre-registration contains.
- Explain why low power corrupts significant results, and how to raise power without recruiting more people.
- Distinguish direct, systematic and conceptual replication by what each licenses.
:::

## Module Logic{{attrs[#blk-7gm5qofd5acf]}}

Module 1 left a question open: can social psychology's findings travel beyond the conditions that produced
them? This module answers with evidence from the past decade, and the answer is mixed enough to require care.
The chapter's structure is itself an argument — each proposed reform gets a *Why?*, an *Uptake*, and a *Costs
and Limitations*. Nothing is presented as a free upgrade.

{{mermaid
graph TD
  A["The system circa 2010:<br/>studies supporting a hypothesis,<br/>judged by shared norms"] --> B["2011 — a structurally ordinary paper<br/>reaches an impossible conclusion"]
  B --> C["The rules of evidence<br/>themselves come into question"]
  C --> D["Eight proposed solutions<br/>each with real costs"]
  C --> E["Manipulation and measurement:<br/>do we know what we measured?"]
  C --> F["Generalizability:<br/>whom is this about?"]
  D --> G["A critical apparatus for<br/>reading Modules 3-12"]
  E --> G
  F --> G
}}

**Visual description:** A flowchart running downward from the pre-2010 reporting system to the 2011 case
that exposed it. That case leads to a single node — the rules of evidence coming into question — which then
branches three ways: the eight statistical and reporting reforms, the deeper question of measurement and
manipulation validity, and the question of who findings are about. All three converge on the critical
apparatus students will apply for the rest of the course.

::: warning
**Read the chapter's stance before its content.** Giner-Sorolla explicitly declines to portray pre-2010
research as lazy or dishonest, holding instead that most researchers really did shape their conception of good work around the system judging them — and that the new system's own rules remain open to challenge.
Both assumptions shape the whole chapter. A student who reads it as an indictment has misread it.
:::

## 2.1 The System of Research and Reporting, Circa 2010{{attrs[#blk-uof1gwdirfvv]}}

::: success
**Learning Objectives**

- Describe the pre-2010 publication model and its evaluative norms.
- Explain the tension between simple consistent rules and complex nuanced judgments.
- Articulate why the chapter refuses a blame narrative.
:::

Social psychology has been reshaped four times methodologically in a relatively short life. Around 1910,
Titchener and Boring steered American psychology away from applied purposes toward an experimentalist,
theory-focused discipline — elevating basic over applied research, an inequality that persisted for decades.
In the 1920s, Floyd Allport established an individual-based social psychology, while collective levels of
explanation continued in sociology's version of the field. (You met both moves in Module 1, from a different
angle.) In the late 1960s and 1970s, the field's relevance to visible social problems came under challenge,
along with the ethics and validity of the standard laboratory model, while European researchers pushed back
against the individualist and experimentalist order. Those same decades produced the fourth: doubts about
whether a single-study article with confident conclusions resting on p < .05 was an adequate basis for
evidence.

Those doubts were not settled by the changes of the 1980s and 1990s. What is new in the past decade is that
**editors, professional societies and other gatekeepers began to act on them.**

The publication system asks two things at once: how valuable are the research ideas, and how strong is the
evidence for the claims? Both judgments face the same structural tension.

:::: cols
::: col
**Easy, consistent rules**
Apply uniformly across manuscripts and reviewers. Cheap to check. But a rule may not capture the construct it
stands for — significance at p < .05 is a rule about a statistic, not a measure of whether a claim is true.
:::
::: col
**Complex, nuanced judgments**
Promise a better fit to what we actually care about. But different people reach different decisions on the
same manuscript, so the process becomes contested and less predictable.
:::
::::

Researchers worked inside this under real pressure: prestigious journals accept no more than about 20% of
submissions, so success required anticipating and meeting the evaluative norms. That is the context in which
the chapter's refusal to blame should be read. Aligning one's standards to the system one is judged by is not
a character flaw; it is what working scientists do.

**Self-check:**

- Name a current evaluation rule in your area that is easy to apply but a poor proxy for what it stands for.
- What would change about your reading of this chapter if you assumed pre-2010 researchers were careless?

## 2.2 The 2011 Collision{{attrs[#blk-56ymomesnbvc]}}

::: success
**Learning Objectives**

- Explain how one paper could destabilize confidence in the field's standards.
- Describe what made it structurally ordinary.
- Evaluate crisis narratives with historical perspective.
:::

In 2011 the field's highest-impact empirical journal published a nine-experiment article by an eminent social
psychologist arguing that a response could be shifted by a stimulus that had not yet
appeared — precognition, stated plainly. The critical feature is not that the claim was outlandish. It is that **the paper looked
structurally like any other paper in the journal**: an extremely novel claim, eight studies with significant
results and one marginal at p = .098, method variations demonstrating that the effect replicated and
generalized, including state-of-the-art reaction-time priming techniques.

If the conclusion were valid, it would overturn generally accepted understandings not only of psychology but
of neurobiology and physics. Since almost no reader was prepared to accept that, the alternative followed
immediately: **the standards that let this paper through were the problem.** Critiques appeared quickly and
targeted the evidential standards rather than merely the result.

::: warning
**Keep some perspective on crisis talk.** The chapter notes that dramatic crisis narratives are usual in this
field's history — amid the "crisis of 1977," someone wrote an article reminding readers of the "crisis of
1927." At the same time it notes real stakes: recent work indicates that making low replication rates public can cost the field the public's confidence. Neither observation cancels the other.
:::

**Self-check:**

- Why does it matter that the 2011 paper was *structurally ordinary* rather than obviously flawed?
- What would it take for a field to distinguish a genuine crisis from a recurring rhetorical one?

## 2.3 Eight Proposed Solutions{{attrs[#blk-238c2j8293x1]}}

::: success
**Learning Objectives**

- State each solution, its target problem, and its principal cost.
- Group the eight by the failure mode each attacks.
- Explain why reporting a statistic differs from having a standard for it.
:::

Eight is too many to memorize as a list. Group them by what each is trying to fix.

| # | Solution | The problem it attacks | A principal cost or limit |
|---|---|---|---|
| 1 | Report effect sizes | "Significant" does not answer "by how much?" | Reporting is enforceable; setting effect-size *thresholds* for publication is a separate and rejected idea |
| 2 | Report null studies within an article | The reported package is assembled after the fact | Requires deciding the study package before the research, which is hard when studies build on each other |
| 3 | Publish more articles with null conclusions | Dead ends get rediscovered repeatedly | Only warranted where theory is solid, methods independently validated, and the analysis can support the null |
| 4 | Report independent direct replication | Whether a finding holds is separate from whether it was found | Costly; and design choices determine whether replicators see the original results |
| 5 | Increase statistical power | Underpowered studies inflate false positives | Sample size is not the only lever — the hypothesis's prior likelihood also drives false-positive risk |
| 6 | Require full disclosure | Undisclosed flexibility in analysis and reporting | On-demand data sharing tends to protect researchers from bad-faith use rather than favor verification |
| 7 | Enable pre-registration and Registered Reports | Exploration presented as confirmation | Constrains legitimate exploratory work unless honest exploration is given its own place |
| 8 | Strengthen theory | Weak constructs make any evidential standard hollow | Slower; and "tighter theory" and "looser exploratory research" are different prescriptions |

Solutions 1–3 govern **what enters the literature**. Solutions 4–5 concern **whether findings hold**.
Solutions 6–7 concern **what researchers reveal, and when**. Solution 8 asks **what the evidence is even
for** — and it is the one the chapter connects forward to measurement.

::: info
**Effect sizes, in the chapter's own reasoning.** They serve meta-analysts, for whom effect size is the common
currency across studies pursuing a question differently. They also correct two opposite misreadings that
occur when only p-values are available: over-interpreting a significant effect from a large sample even when
it is small in raw or standardized terms, and over-interpreting a non-significant result as showing that
nothing is going on. And they let readers — including lay readers, if units are interpretable — gauge the
practical possibilities of a finding.
:::

:::: tabs
::: tab Problem
A journal proposes: "To improve rigor, we will reject any manuscript whose central effect size falls below a
threshold of practical significance, even where the effect is reliably different from zero." Evaluate this
proposal using the chapter's reasoning.
:::
::: tab Solution
The proposal should be rejected, and the chapter is unusually direct about it — the answer to whether
manuscripts should be rejected on effect-size thresholds is "a resounding no." The reasoning has several
strands.

**It confuses reporting with standard-setting.** Checking that effect sizes are reported is straightforward
for an editor; a manuscript missing them can simply be returned. Deciding that effects below some magnitude
are not publishable is a different act entirely, and one that no consensus supports.

**Small effects can be substantively important.** Practical significance depends on the outcome, the cost of
intervention, and the scale of application. An effect that is trivial in one setting can matter greatly when
it operates across a population or accumulates over time. A single numeric threshold cannot encode that.

**It would recreate the pathology being fixed.** The complaint about p < .05 was that a threshold on a
statistic became a proxy for whether a claim was worth publishing, distorting what researchers pursued and
reported. Installing a threshold on effect size instead changes the statistic while preserving the structure,
and creates a fresh incentive toward designs and measures that inflate effect sizes.

**It cuts against Solutions 2 and 3.** Those aim to get null and inconvenient results into the literature so
dead ends are identified rather than repeatedly stumbled into. A magnitude threshold suppresses precisely the
findings that would let a field learn an effect is small.

**What the chapter endorses instead:** conclusions drawn from low effect sizes should be *qualified* — the
remedy is calibrated interpretation, not exclusion. Note the general shape of this answer, since it recurs
across all eight solutions: a reform that removes a judgment by replacing it with a rule tends to relocate the
problem rather than solve it.
:::
::::

**Self-check:**

- For each of the four groupings, name the failure mode it targets in one sentence.
- Which solution do you think has the worst cost-to-benefit ratio in your own research area, and why?

## 2.4 Manipulation and Measurement{{attrs[#blk-9lbqs15iioft]}}

::: success
**Learning Objectives**

- Explain why theory quality and method quality are the same problem viewed twice.
- Describe questionable measurement practices and their consequences.
- Explain what a manipulation check can and cannot establish.
:::

The chapter places methods immediately after theory deliberately. The wish-list for better theorizing
includes tighter construct definitions — which is exactly what would produce clearer operationalizations of
manipulation and measurement. Greenwald's formulation captures it: **nothing carries more theory in it than a well-chosen method.** Connecting effects to explanations requires specifying which part of a method is essential to
testing the theory and which is incidental.

One consequence is sharp. Meta-analysis cannot estimate effect size well when the studies pooled were done in very different ways and each one's weight depends on nothing better than how often that approach happened to be published.
The chapter's image for the resulting number is a zoo: pool every resident, report a mean body weight, and you
have an arithmetically sound figure that **describes no animal and estimates nothing**.

**Questionable measurement practices.** Critiques of psychology's low priority on valid construct
measurement — the "measurement, schmeasurement" attitude — identify undisclosed flexibility in measurement
decisions such as which scale items to use, alongside poor reliability and unvalidated scales. Studies of
measurement practice support the conclusion that questions of measurement quality are passed over as a matter of course, both in doing research and in publishing it.

**Manipulation rigor.** For decades, a positive result from an experiment was generally taken as sufficient
evidence that the manipulation worked. That inference collapses in two situations the reforms above make
common: when independent teams attempt replication, and when a Registered Report may be published with null
results. In both, the crucial question is whether a negative result reflects a genuine near-zero effect or
simply a failure to set the experiment up correctly.

::: warning
**What a manipulation check does not settle.** A check administered in the same sitting cannot on its own settle whether a manipulation was valid, in either direction. Worse, asking participants directly can alter the procedure itself, by tipping them off to what is being varied — which is why nonverbal
checks have been suggested as alternatives. There is also a stronger position in the literature that
manipulation checks are unnecessary because they inform us only about effects at an operational level.
:::

**Self-check:**

- Explain the zoo analogy in your own words, then name a meta-analysis in your area it might apply to.
- If a replication attempt yields null, what evidence would let you decide between "no effect" and "failed manipulation"?

## 2.5 Challenges to Generalizability{{attrs[#blk-2edjv5wq4jyn]}}

::: success
**Learning Objectives**

- Explain what WEIRD names and what it has been criticized for.
- Describe the structural mechanisms producing generalizability bias.
- Explain how implicit claims of generality operate in ordinary writing.
:::

The doubts are old. Critics noted the growing reliance on university student samples in the 1950s and 60s and
asked what could be concluded from so limited a range of human culture and experience. Others questioned why
laboratory research was glorified over real-world relevance, or objected to easy self-report attitudinal
measures displacing more effortful observation of actual behavior.

**WEIRD** — Western, Educated, Industrialized, Rich Democracies — focused attention on the cultural
limitations of psychology's participants, though the acronym's scope has itself been criticized. The chapter's
more important contribution is to show that the problem is **structural, not a sampling footnote**. There is
an implicit center–periphery ordering, the United States, and sometimes Canada, at the middle; then the mostly white English-speaking countries; then continental Europe outside the Anglophone world; then eastern Europe, east Asia and the global South. Within countries, rural populations are understudied relative to urban
ones, and people living outside agrarian or industrial society barely appear at all.

The mechanisms are documented rather than asserted:

- Researchers, journal editors and research populations are drawn overwhelmingly from more central nations and cultures.
- This supports an implicit bias in which research on central populations is treated as **normal and automatically generalizable**, while peripheral groups are seen as special cases needing labels and explanation.
- Bibliometric work finds that studies using central-population samples are **less likely to signal their origin in the title** — and that this discrepancy leads peripherally-oriented research to be perceived as less important.
- A survey of social psychologists worldwide records pervasive discrimination against those working in peripheral zones: hearing that their work is too narrow or of no general interest, and being asked for demonstrations of validity central-zone submissions never face — an added comparison group drawn from a central population, or a separate validation of their measures.

::: info
**How implicit generality works.** Few articles explicitly claim to describe all humankind. But as Henrich and
colleagues observe, a typical article does not claim to discuss "humans" — it simply describes a decision
bias, a psychological process, a set of correlations, without addressing generalizability, while linking the
findings to "people." The claim is made by omission. Watch for this in every paper you read this term; it is
one of the easiest things to spot once named, and one of the hardest to unsee.
:::

**Self-check:**

- Take an abstract from a later module's reading list. Does it signal its sample's origin? Would it if the sample were from elsewhere?
- What would it take for a finding to earn an unqualified claim about "people"?

## 2.6 From Principle to Practice: The Exploratory–Confirmatory Line{{attrs[#blk-wwojepqd7pcb]}}

::: success
**Learning Objectives**

- Distinguish an exploratory research question from a confirmatory hypothesis, and exploratory from confirmatory *analysis*.
- Explain what HARKing is and why it damages the evidential value of a result.
- Describe what a pre-registration actually contains.
:::

Sections 2.1–2.5 are about what the field decided. This section and the two that follow are about what a
researcher *does* — the craft that the reforms imply.

The cleanest way to see it is that **question type and analysis type vary independently**, giving four cells
rather than two:

| | Exploratory research question<br/>*(information gathering, theory building)* | Confirmatory hypothesis<br/>*(theory testing; a directional prediction made in advance)* |
|---|---|---|
| **Exploratory analysis**<br/>*(data-dependent decisions)* | Asking whether X affects Y and letting the data guide the analysis. Legitimate, and honestly labelled. | A prediction exists, but the analysis is still shaped by what the data look like. The weakest cell to report as confirmation. |
| **Confirmatory analysis**<br/>*(data-independent decisions)* | Asking whether X affects Y under an analysis plan fixed in advance — the manipulation, the measure construction and the test all specified. | A directional prediction *and* a pre-specified plan. The strongest evidential claim available. |

An exploratory question is driven by intuition where no strong theory exists, and its purpose is to *generate*
theory. A confirmatory hypothesis follows from a theory strong enough to be wrong, and its purpose is to put
that theory at risk.

::: warning
**HARKing** — hypothesizing after results are known — is presenting a hypothesis formed *after* seeing the
data as though it had been made in advance. It moves a result from the top-left cell to the bottom-right one
without any of the epistemic work that move requires, and it erases the distinction between generating a
theory and testing it. That erasure is the damage: a field that cannot tell its exploratory results from its
confirmatory ones cannot tell which of its claims have actually been risked.
:::

**Pre-registration** is the practical answer: fix the plan publicly before the data exist, so the
exploratory–confirmatory boundary is a matter of record rather than recollection. A serious pre-registration
specifies the target sample size and the stopping rule; inclusion and exclusion criteria, including how
attention-check failures will be handled; the manipulations and conditions; how each predictor will be
constructed; the dependent measures and their construction; any planned covariates; the specific statistical
tests naming their operational variables; any planned follow-up or subgroup analyses; and the plan for Type I
error control across multiple comparisons.

::: info
**Do not follow a pre-registration blindly.** A plan written before the data exist can turn out to be wrong —
a measure fails, an assumption is violated, a condition does not run as intended. The point of
pre-registration is not to bind the researcher's hands but to make departures *visible*: report the planned
analysis, report the deviation, and say why. A pre-registration that is silently abandoned is worse than none,
because it lends unearned credibility.
:::

The wider practice this belongs to is **transparency across the whole research cycle**: sharing plans,
materials, data, analysis code and preprints — through repositories such as the Open Science Framework and
preprint servers such as PsyArXiv. Note how this connects to §2.3: Solutions 6 and 7 are the *policy*, and
this is the *practice*.

**Self-check:**

- Place a study you know in one of the four cells. What would it take to move it down and to the right?
- Why is a deviation from a pre-registered plan not, by itself, a problem?

## 2.7 Power, and What to Do About It{{attrs[#blk-kdo7zlpt5327]}}

::: success
**Learning Objectives**

- Explain why low power is a problem for significant results, not only null ones.
- Describe several ways to raise power other than collecting more participants.
- Explain what makes a null result informative.
:::

The intuitive view of statistical power is that it matters when you fail to find an effect. That view is
wrong, and correcting it is the most useful thing this section does.

::: danger
**Low power damages the results you do find.** Underpowered studies produce estimates that swing wildly from
sample to sample. Below roughly 50% power, the average *significant* effect size is dramatically inflated —
because only the large, lucky estimates clear the significance threshold. Below about 10% power, effect-size
estimates can point in the wrong direction entirely. A significant result from an underpowered design is
therefore not merely weak evidence; its magnitude, and possibly its sign, are untrustworthy.
:::

Low power also lowers the **positive predictive value** of a literature — the proportion of significant
findings that correspond to real effects — which is the same reasoning that made the 2011 case in §2.2
unpersuasive despite eight significant studies.

**Raising power without simply recruiting more people.**

- **Within-subject designs** are substantially more efficient than between-subject designs for the same number of participants, because each person serves as their own comparison.
- **Sequential analysis**: decide the smallest effect worth detecting, compute the sample size that would detect it, and set interim analysis points in advance — stopping early if the criterion is met. Because the stopping rule is specified beforehand, this is not the same as peeking.
- **Aggregating across small studies** designed to combine, rather than treating each as standalone.
- **Multi-laboratory collaboration**, which also buys generalizability across sites.
- **Bayesian approaches**, which allow evidence to accumulate without a fixed-N commitment.

::: warning
**A trap in a priori power analysis.** If the effect-size estimate you plan around is too optimistic — as
published estimates often are, for exactly the inflation reason above — the resulting sample will be too small
and the study underpowered. Planning around a *large* expected effect is how well-intentioned researchers
build underpowered studies and waste their resources.
:::

**Reporting power honestly** takes more than one form, and which you use depends on what constrained the
design. An **a priori** analysis states the effect-size estimate, its source, the resulting target N, and any
padding for expected exclusions. A **sensitivity** analysis fits the case where N was fixed by circumstance —
data collected until the end of a term, say — and reports what effect size that N could detect at a given
power, ideally against a benchmark for typical effects in the field. A **range** analysis reports power across
the plausible interval of effect sizes from prior work, which is the most honest option when the literature
disagrees with itself.

**When is a null result informative?** Only under conditions you must establish rather than assume: the study
had enough power that a real effect would probably have been detected; the result is unlikely to be a Type II
error; a **manipulation check** was included; and the analysis can support the null rather than merely fail to
reject it — through equivalence testing or a Bayesian approach.

::: info
**The manipulation check does specific work here**, and it resolves the question §2.4 left open. If the
manipulation moved the check but the dependent variable did not move, you can reasonably infer that the
manipulation genuinely does not affect the outcome. If the manipulation moved *neither*, the more likely
inference is that you failed to manipulate the construct at all. The two cases look identical in the outcome
data and are distinguished only by the check.
:::

**Self-check:**

- Why is a significant result from a 20% powered study problematic in a way a null result from the same study is not?
- Given a fixed sample you could not control, which form of power reporting is honest?

## 2.8 Programmatic Research: Replication and Cumulative Evidence{{attrs[#blk-4ml00nftzllb]}}

::: success
**Learning Objectives**

- Distinguish direct, systematic and conceptual replication by what each licenses.
- Explain what a constraints-on-generality statement does.
- Describe publication bias and the partial remedies available.
- Characterize the dispute over large-scale replication estimates.
:::

A single study is always limited and always biased in some respect. The useful image here is a wall: each
study is one brick, and the point of methodological care is to make each brick solid enough to build on. It
follows that replication is not a policing activity but the ordinary way a literature accumulates — and that
the three kinds of replication answer three different questions.

| Kind | What it varies | What extra confidence it buys |
|---|---|---|
| **Direct** | As little as possible — the same operationalizations, same population, same procedures | That the specific manipulations and measures produce the effect at all. Especially valuable when the original study departed from its own pre-registered plan. |
| **Systematic** | Incidental features of the context — different stimuli, a different cover story, a different experimenter, a different sample | That those details were genuinely irrelevant, which is the assumption the original implicitly made. Buys generalizability of the relation between those operationalizations. |
| **Conceptual** | The operationalization of the theoretical construct itself — a different measure, a different behavioral outcome | That the results mean what they were claimed to mean. Useful when you are confident about a pattern among operational variables but unsure they tap the constructs of interest. |

Note the order of dependency: a conceptual replication that succeeds while the direct replication fails tells
you something quite different from one that succeeds alongside it.

**Constraints on generality.** Rather than leaving scope to be inferred, a paper can state explicitly how far
its authors expect the finding to hold — across which stimuli, samples and situations, and why. This converts
the implicit generality claim of §2.5 into a falsifiable statement that later work can test, and it gives a
replication a criterion for whether it was a fair test.

**Publication bias and meta-analysis.** Because positive results are published preferentially, a meta-analysis
over the published record inherits that selection. Three partial remedies: lean on **moderator analyses**,
which are less sensitive to the bias than an overall average; report **all** results within a paper — if four
of six tests were significant, report six — so that a within-paper meta-analysis is possible; and actively
seek unpublished work. Combine this with §2.4's warning about pooling studies done in very different ways, and the
lesson is that a meta-analytic average is a claim requiring defence, not a neutral summary.

::: warning
**The dispute over replication estimates is itself worth studying.** After a large multi-laboratory project
published an estimate of psychology's reproducibility, a published critique argued that the confidence
intervals had been used inappropriately, that replication samples were sometimes drawn from different
populations than the originals, that endorsement of the replication protocols by original authors was
incomplete, and that a different large replication effort had found a considerably higher success rate. The
reply defended the interval methods, disputed the characterization of the other project's results, and made a
sharper point: sample variation across a direct replication is not an infidelity but a *test of
generalizability*. The common ground that emerged is the part students most often miss — that such a project
cannot by itself license a pessimistic verdict on the field, and that what counts as a faithful replication is
a substantive question rather than a technicality. Read the exchange rather than the headline.
:::

**Self-check:**

- Which kind of replication would you run first for a finding you doubt, and why?
- Write a one-sentence constraints-on-generality statement for a study in your own area.
- What is the strongest version of the argument that a failed replication tells us little?

## Synthesis{{attrs[#blk-e6v8nil98xom]}}

The thread of this module is that **evidential standards, measurement validity, and generalizability are one
problem, not three.** A statistical reform tells you whether an effect is reliably detected; it says nothing
about whether the instrument measures the construct, and nothing about whom the result describes. A field can
raise its power, pre-register everything, and share all its data while still not knowing what it measured or
whom it measured it on. That is why the chapter moves from the eight solutions to measurement and then to
generalizability rather than stopping at the statistics — and why Solution 8, strengthen theory, is the hinge
between them.

For the rest of this seminar, carry four questions into every empirical reading. Was the evidential standard
adequate, and which of the eight solutions bears on it? Does the study establish that its manipulation did
what it claims and its measures capture what they name? Who were the participants, and does the paper's
language claim more than its sample supports? And — keeping the chapter's own posture — what would the
authors have had to do differently given the incentives they faced, rather than what would an ideal
researcher have done?

Sections 2.6 to 2.8 close the loop between policy and craft. The eight solutions say what the field decided;
pre-registration, power planning and programmatic replication are what a researcher actually does about it.
Notice that the same idea keeps returning in different clothes: make the reasoning auditable. Pre-registration
makes the analysis plan auditable, a stated stopping rule makes sequential testing auditable, a
constraints-on-generality statement makes the scope claim auditable, and reporting all six tests rather than
the four that worked makes the selection auditable. None of these is a threshold on a statistic, which is
exactly why they survive the critique that sank the effect-size threshold in §2.3.

Module 3 turns to substance for the first time, taking up how people perceive and explain other minds. Bring
these questions with you; they are what makes a seminar discussion of an empirical paper more than a summary.

## Asset and License Record for This Module{{attrs[#blk-y3inwudaz8x5]}}

| Asset | Source URL | License | Attribution |
|---|---|---|---|
| *(none — this module embeds no images)* | — | — | The one diagram is an inline `{{mermaid}}` figure generated from this document's own source and carries the package license, CC-BY-SA-4.0. |

---

**Source attribution.** Facts and findings in this document are drawn from Gilbert, Fiske, Finkel, & Mendes (Eds.), The Handbook of Social Psychology (6th ed.), Situational Press — https://doi.org/10.70400/NYKH3013 — published open access under CC BY-NC-ND 4.0 (https://creativecommons.org/licenses/by-nc-nd/4.0/). Cited as a source of facts and findings; no text or figures adapted. This document is licensed CC BY-SA 4.0.
