# Guide for Writing Referee Reports at Top Finance/Economics Journals

## Purpose of This Document

This document captures tacit knowledge about what referees at top-3 finance journals (Journal of Finance, JFE, RFS) and top economics journals (AER, QJE, JPE, Econometrica, REStud) look for when evaluating papers, and how to provide feedback that is genuinely useful to authors.

---

## Part I: What Top Journals Require

### 1. The Contribution Bar

**First-order question**: Does this paper make a contribution that will be cited 20 years from now?

Top-3 journals ask:
- **Novelty**: Is this the first paper to document X, or the first to explain Y with mechanism Z?
- **Importance**: Does this matter for a broad audience, or only specialists?
- **Surprise**: Does this overturn conventional wisdom, or confirm what we suspected?
- **Generalizability**: Does it speak to universal economic forces?

**The hierarchy of contributions** (from most to least valued):
1. New economic mechanism with clear identification
2. New important fact that changes how we think about a topic
3. New methodology that enables future research
4. Quantitatively important refinement of existing estimates
5. Replication or extension to new setting (rarely sufficient alone)

### 2. Identification and Causality

**The central question**: Can the reader believe the estimates?

**Hierarchy of identification** (from strongest to weakest):
1. Randomized experiment
2. Natural experiment with clear exclusion restriction
3. Difference-in-differences with parallel trends
4. Regression discontinuity
5. Instrumental variables with defensible exclusion
6. Selection-on-observables with extensive controls
7. Descriptive correlations

**What referees scrutinize**:
- **Endogeneity**: What omitted variables could drive both X and Y?
- **Reverse causality**: Could Y cause X instead?
- **Selection**: Are the treated/control groups comparable on unobservables? Is the treatment random? 
- **Measurement error**: Could mismeasurement bias estimates toward/away from zero?
- **External validity**: Would this replicate in other settings?


### 3. Economic Mechanism

**The question editors ask**: "Why should I care about this correlation?"

A paper that documents X is associated with Y is incomplete without answering:
- **Why** does this relationship exist?
- **Through what channel** does X affect Y?
- **What economic model** generates this prediction?

**Good mechanism analysis**:
- Derives testable predictions from theory
- Shows heterogeneity consistent with mechanism (effect stronger when mechanism should be stronger)
- Rules out alternative mechanisms
- Provides direct evidence on intermediate outcomes

**Common mechanism failures**:
- Offering multiple mechanisms without adjudicating between them
- Mechanism is asserted, not tested
- Theory section disconnected from empirical tests

### 4. Robustness and Specification

**What demonstrates robustness**:
- Results survive across reasonable alternative specifications
- Main effects not driven by outliers or particular subsamples
- Results stable across different fixed effects structures
- Placebo tests fail (no effect where there shouldn't be one)

**What raises specification concerns**:
- Results sensitive to inclusion/exclusion of specific controls
- Standard errors change dramatically with clustering choice
- Effects driven by small number of observations
- Results flip sign for certain subgroups without explanation
- Too many controls relative to identifying variation

### 5. Data Quality and Measurement

**Questions referees ask**:
- Is the outcome variable measuring what authors claim?
- Are key variables measured with error? How does this bias results?
- Is the sample representative? Selection into sample?
- Are there data limitations that could drive results?

**Sample construction scrutiny**:
- Why are observations dropped?
- How do dropped observations differ from kept observations?
- Is the sample size adequate for the analysis?
- Are there enough "treated" observations for subgroup analyses?

### 6. Relation to Literature

**What referees expect**:
- Clear positioning relative to closest 5-10 papers
- Explicit statement of what's new versus what's known
- Engagement with papers that might challenge findings
- No "straw man" literature review

**Literature review failures**:
- Missing key papers (suggests authors unfamiliar with field)
- Dismissing related work without engagement
- Claiming novelty that doesn't exist
- Not citing papers that find different results

### 7. Writing and Presentation

**Top-3 standards**:
- Introduction clearly states contribution in first 2-3 paragraphs
- Main result visible by page 5-7
- Paper is self-contained (reader shouldn't need appendix to understand main results)
- Figures and tables are clear, properly labeled, interpretable standalone
- Economic magnitudes reported (not just statistical significance)

**Presentation failures**:
- Results buried in middle of paper
- Excessive qualification and hedging
- Tables with too many columns/panels
- Figures without clear takeaway
- Introduction that doesn't state the answer

---

## Part II: What Makes Feedback Useful

### 1. The Referee's Role

**You are NOT**:
- A gatekeeper trying to reject papers
- A competitor trying to sink rivals
- An expert asserting superiority

**You ARE**:
- A constructive critic helping authors improve
- A representative of the median reader
- An advisor to the editor on publishability

### 2. Structure of a Useful Report

**Opening paragraph**:
- Brief summary of what paper does (shows you understood it)
- Overall assessment (enthusiasm level, major concerns)
- Clear recommendation (reject/R&R/accept)

**Major comments** (3-5 issues that affect publishability):
- Each comment clearly stated as a concern
- Explanation of why this matters
- Suggestion for how to address (if possible)
- Be specific: cite page numbers, equations, tables

**Minor comments** (presentation, typos, clarifications):
- Numbered list for easy reference
- Brief and actionable

### 3. Principles for Constructive Feedback

**Be specific, not vague**:
- BAD: "The identification is weak"
- GOOD: "The main concern is that municipality fixed effects absorb the identifying variation, but municipalities differ in many ways beyond housing returns. Specifically, Table 3 shows that adding municipality FE reduces the coefficient by 60%, suggesting location is proxying for something. The paper would be strengthened by: (a) showing what municipality characteristics drive returns, and (b) providing a test that distinguishes between sorting and causal effects of location."

**Be honest about severity**:
- Distinguish between fatal flaws and fixable issues
- If a problem is addressable with existing data, say so
- If a problem requires new data or new identification, be clear

**Offer solutions, not just criticism**:
- If you identify a problem, suggest how to fix it
- Point to papers that addressed similar issues
- Acknowledge when a problem may be unavoidable

**Be fair to the paper's goals**:
- Don't ask the paper to be a different paper
- Evaluate what the paper claims to do, not what you wish it did
- Recognize that every paper has limitations

**Acknowledge strengths**:
- Note what the paper does well
- Credit novel contributions
- Recognize careful work even when disagreeing

### 4. Common Referee Mistakes to Avoid

- **Asking for impossible tests**: "You should run an RCT"
- **Moving the goalposts**: "Now that you did X, you need to do Y"
- **Scope creep**: "You should also study Z" (different paper)
- **Vague objections**: "I'm not convinced" (convince me of what?)
- **Aggressive tone**: Personal attacks, dismissiveness
- **Perfectionism**: No paper is perfect; is this publishable?
- **Misreading the paper**: Criticizing something the paper didn't claim

### 5. Calibration Across Journals

**Top-3 Finance (JF, JFE, RFS)**:
- Expect clean identification or compelling new facts
- High bar for "importance" - must matter beyond specialty
- Strong preference for US data (international needs justification)
- Theory papers rare; empirical must have mechanism
- ~5-8% acceptance rate; R&R is a strong positive signal

**Top Economics (AER, QJE, JPE)**:
- Broader audience expectation
- More emphasis on economic mechanisms
- Design-based identification strongly preferred
- Will accept international data if generalizable
- Can publish "big picture" papers that finance journals won't

**Field journals**:
- More specialist audience
- Lower bar for generalizability
- Can publish incremental contributions
- More open to international/specialized settings


## Part III: The Decision Framework

### Recommend Accept (rare, <5% of submissions)
- Clear, important contribution
- Clean identification
- Well-written, ready for publication
- No major concerns

### Recommend Revise and Resubmit
**Strong R&R** (likely to publish after revision):
- Good contribution if concerns addressed
- Concerns are specific and addressable
- Authors have path to success

**Weak R&R** (may not publish even with revision):
- Contribution uncertain
- Major concerns about identification
- Substantial revision required

### Recommend Reject
- Contribution below journal bar
- Fundamental identification problems
- Would require complete rewrite
- Better suited to field journal

### Key Question for Editor
"If the authors perfectly address every concern I've raised, would this paper be publishable at this journal?"
- If yes → R&R
- If no → Reject (or suggest resubmission to appropriate journal)

---

## Part IV: Writing the Report

### Template Structure

```
SUMMARY
[2-3 sentences on what the paper does]
[1 sentence on main finding]
[1 sentence on overall assessment]

RECOMMENDATION: [Accept / Revise and Resubmit / Reject]

MAJOR COMMENTS

1. [Concern title]
[Explanation of concern - what's the issue?]
[Why it matters - how does this affect interpretation?]
[Suggestion - how might authors address this?]

2. [Continue for 3-5 major issues]

MINOR COMMENTS
1. Page X: [specific comment]
2. Table Y: [specific comment]
[etc.]
```

### Tone Calibration
- Be direct but respectful
- Criticism should be constructive
- Acknowledge difficulty of research
- Write report you'd want to receive

---

*This guide should be consulted before writing the referee report, and used as a checklist to ensure comprehensive, constructive feedback.*