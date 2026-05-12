# Accessibility Standards, Disability Bias, and the Possibility of Agentic AI

## Accessibility standards are not neutral

Accessibility standards are often treated as objective and universal.

WCAG, EN 301 549, and institutional guidance such as the BBC’s accessibility standards are commonly presented as authoritative frameworks for creating inclusive digital experiences. They are enormously valuable. Without them, accessibility would likely remain inconsistent, underfunded, poorly understood, and difficult to operationalise at scale.

Yet accessibility standards are not neutral.

They are shaped by:

- the historical context in which they were created
- the disabilities most represented during their development
- the technologies available at the time
- legal and procurement pressures
- what could realistically be standardised and tested
- the organisational systems expected to implement them
- and broader cultural assumptions about disability, usability, communication, and participation

This does not mean accessibility standards are inherently exclusionary or intentionally biased.

It means they reflect priorities.

And priorities inevitably create emphasis, gaps, trade-offs, and sometimes unintended forms of exclusion.

As accessibility practice matures, a difficult but increasingly important question emerges:

> Do our accessibility standards sometimes privilege certain disability experiences over others?

Closely followed by another:

> Could emerging forms of agentic AI help us move accessibility from standardised compliance toward adaptive experiential inclusion?

These questions are uncomfortable.

But they may define the next era of accessibility.

---

# Accessibility standards emerged from necessary constraints

To understand potential biases within standards, it is important to understand the problems those standards were originally trying to solve.

The web of the 1990s and early 2000s was frequently unusable for many disabled people.

Common barriers included:

- missing image descriptions
- inaccessible forms
- keyboard traps
- content unreadable by screen readers
- media without captions
- low colour contrast
- inaccessible document structures
- inaccessible navigation patterns
- device-specific assumptions

The creation of WCAG provided something transformational:

- shared language
- measurable criteria
- technical interoperability expectations
- legal defensibility
- procurement requirements
- scalable governance
- and industry accountability

The emphasis on testability was not accidental.

It was essential.

A requirement such as:

> “All functionality must be operable through a keyboard interface”

is comparatively testable.

Similarly:

- colour contrast ratios
- semantic structure
- focus visibility
- captions
- accessible names
- heading hierarchy
- reflow
- text alternatives

can all be reasonably standardised.

This created enormous progress.

In many ways, accessibility’s strongest successes came from making disability needs visible within technical systems.

The result was a major improvement for many:

- blind users
- low vision users
- keyboard-only users
- many motor-impaired users
- D/deaf users requiring captions
- and users relying on assistive technologies

These achievements should not be minimised.

They fundamentally changed digital access.

But standardisation also created a subtle structural effect:

> Accessibility became increasingly shaped by what could be measured.

And not all human experiences are equally measurable.

---

# The problem of testability bias

One of the most significant structural biases within accessibility standards is testability bias.

Put simply:

> Needs that are easier to define technically tend to receive stronger formal representation.

This affects how accessibility is prioritised, funded, audited, automated, procured, and taught.

For example:

It is relatively straightforward to determine whether:

- an image has alt text
- a button has an accessible name
- captions exist
- a form field has a label
- colour contrast meets thresholds
- focus order exists

These can often be:

- automatically detected
- manually audited
- integrated into tooling
- enforced contractually
- and measured consistently across organisations

But many accessibility barriers do not behave this way.

Examples include:

- cognitive overload
- decision fatigue
- sensory overwhelm
- executive dysfunction
- emotional regulation barriers
- memory burden
- ambiguity
- social interpretation complexity
- trauma responses
- fatigue accumulation
- attention fragmentation
- information anxiety
- contextual confusion
- dysregulating interaction patterns

These experiences are:

- contextual
- personal
- dynamic
- and often highly situational

A technically conformant interface may still be exhausting.

A screen reader-compatible system may still create overwhelming cognitive load.

A fully keyboard-accessible workflow may still be impossible to sustain for someone with fatigue, chronic pain, ADHD, or brain fog.

This creates an important imbalance:

> The most measurable accessibility barriers often become the most institutionally visible barriers.

That does not mean cognitive accessibility is ignored.

The W3C’s Cognitive and Learning Disabilities Accessibility Task Force (COGA) has spent years attempting to expand accessibility thinking beyond purely technical interoperability.

But cognitive accessibility exposes a difficult truth:

> Human usability is often resistant to standardisation.

And modern accessibility governance systems are deeply dependent on standardisation.

---

# Which disability groups tend to be best represented?

Historically, formal accessibility standards have often been strongest in supporting:

- screen reader interoperability
- keyboard interaction
- visual perception barriers
- text alternatives
- media alternatives
- device-independent access

This has been enormously beneficial.

In many ways, blind users and screen reader accessibility became foundational to modern accessibility thinking.

That influence shaped:

- semantic HTML adoption
- ARIA development
- assistive technology interoperability
- accessible forms
- structured navigation
- alternative text expectations
- and accessibility testing culture itself

Similarly, captioning requirements significantly improved media accessibility for many D/deaf users.

These were not accidental successes.

They reflected sustained advocacy, identifiable technical barriers, and the ability to operationalise requirements.

However, other disability experiences have historically received weaker structural representation.

This is particularly visible around:

- neurodivergence
- cognitive disabilities
- fluctuating conditions
- fatigue-related impairments
- sensory processing differences
- mental health-related cognitive barriers
- communication disabilities
- and complex intersectional access needs

The issue is not simply omission.

It is that many of these experiences challenge the assumptions underlying traditional accessibility systems.

For example:

## Cognitive accessibility is often non-binary

A user may technically be able to complete a task.

But:

- only with extreme effort
- after repeated mistakes
- with emotional distress
- or with unsustainable levels of concentration

Traditional compliance systems struggle to represent this.

## Neurodivergent needs are often contradictory

Some users prefer:

- minimal interfaces
- reduced information density
- simplified language
- predictable layouts

Others prefer:

- high information density
- precision and specificity
- detailed control
- explicit structure
- reduced ambiguity

There is no single universally “accessible” interface.

This challenges compliance models that seek universal rules.

## Fatigue and fluctuating impairments are difficult to model

A workflow that is accessible for ten minutes may become inaccessible after forty.

An interface usable on a good day may become impossible during:

- migraine
- Long COVID fatigue
- fibromyalgia flare-ups
- medication side effects
- autistic burnout
- ADHD overwhelm
- stress
- grief
- or cognitive exhaustion

Most accessibility standards are comparatively static.

Human capacity is not.

---

# Accessibility improvements can create friction for other groups

One of the most difficult realities in inclusive design is that accessibility needs are not always perfectly aligned.

There are situations where improving experiences for one group may create barriers for another.

This does not mean accessibility is impossible.

It means inclusion requires negotiation, flexibility, and humility.

For example:

## Verbosity versus clarity

Some screen reader users benefit from:

- extensive context
- hidden instructions
- detailed labels
- rich ARIA descriptions

But excessive verbosity can increase:

- cognitive load
- memory burden
- attentional fatigue
- distraction
- and frustration

Especially for:

- ADHD users
- autistic users
- users with brain fog
- users experiencing fatigue
- or people processing information under stress

## Motion reduction versus spatial orientation

Reduced motion settings help many users avoid:

- vestibular triggers
- sensory overwhelm
- nausea
- migraine triggers

Yet some motion and transition cues support:

- orientation
- continuity
- spatial understanding
- interaction predictability

Again, there is no universally correct solution.

## Simplification versus precision

Simplified language may support:

- people with intellectual disabilities
- language processing differences
- dyslexia
- cognitive fatigue
- low literacy

But oversimplification may:

- remove important nuance
- reduce trust
- feel infantilising
- obscure technical detail
- or frustrate autistic users who value precision and explicitness

Accessibility is therefore not only about removing barriers.

It is also about balancing competing access needs.

This is one reason why inclusive design increasingly emphasises:

- adaptability
- user choice
- personalisation
- and participatory design

rather than assuming a single universally optimal interface.

---

# EN 301 549 and procurement-driven accessibility

EN 301 549 introduces another important dynamic.

Unlike WCAG alone, EN 301 549 operates heavily within procurement and regulatory systems.

This changes the incentives.

Procurement frameworks favour:

- measurable evidence
- repeatable audits
- contractual accountability
- documentation
- vendor comparability
- and legal defensibility

This can unintentionally reinforce compliance-centric behaviour.

The result is sometimes a disconnect between:

- technical conformance
- and lived accessibility experience

An organisation may:

- pass audits
- produce conformance statements
- satisfy procurement requirements
- and still create exhausting or exclusionary user journeys

because experiential usability is harder to formalise.

This creates another form of structural bias:

> Accessibility work may prioritise what organisations can prove over what users actually experience.

This is not unique to accessibility.

It is a common outcome in governance systems.

But accessibility is especially vulnerable because many barriers are experiential rather than binary.

---

# Why the BBC’s guidance often feels more human-centred

Many practitioners view the BBC’s accessibility guidance differently from pure standards frameworks.

Partly because the BBC has historically approached accessibility not only as a compliance obligation, but also as:

- editorial quality
- communication quality
- audience inclusion
- and product usability

The BBC guidance often places stronger emphasis on:

- understandable language
- clear structure
- meaningful content hierarchy
- media accessibility
- multimodal communication
- practical user comprehension
- and consistency across journeys

This tends to support broader inclusion.

Especially for:

- cognitive accessibility
- older audiences
- stressed users
- low confidence users
- users with mixed access needs
- and people outside traditional assistive technology models

The BBC’s guidance frequently feels more experiential because broadcasting and media inherently involve:

- narrative comprehension
- emotional engagement
- contextual understanding
- timing
- communication clarity
- and multimodal consumption

However, even highly respected guidance is not neutral.

Institutional guidance still reflects:

- operational realities
- audience assumptions
- production constraints
- and dominant cultural expectations

No accessibility framework can fully escape the perspectives embedded within its creation.

---

# Accessibility standards were designed for systems, not people

This statement may initially sound unfair.

But it highlights an important distinction.

Accessibility standards are often optimised for:

- consistency
- governance
- interoperability
- legal enforceability
- procurement
- scalability
- and engineering implementation

Humans are not consistent.

Disabled people are not a homogeneous group.

And accessibility experiences are often contextual, emotional, situational, and dynamic.

A person’s accessibility needs may change based on:

- energy levels
- stress
- environment
- device
- familiarity
- medication
- sensory conditions
- time pressure
- emotional state
- cognitive fatigue
- and accumulated friction

Current standards frameworks struggle to model this complexity.

This is not necessarily a failure.

It may simply reflect the limits of static standards.

Which raises an important question:

> What happens when accessibility systems become adaptive instead of static?

---

# Agentic AI may fundamentally change accessibility

Much current accessibility thinking assumes:

- fixed interfaces
- predefined interaction models
- standardised content structures
- universal experiences

But agentic AI introduces the possibility of:

- adaptive interfaces
- personalised interaction flows
- context-aware assistance
- conversational mediation
- dynamic simplification
- and real-time experiential adaptation

This could profoundly reshape accessibility.

Not merely by automating compliance.

But by responding to human variability itself.

---

# From compliance accessibility to experiential accessibility

Traditional accessibility systems largely ask:

> Can the user technically access the interface?

Agentic systems may instead ask:

> Is this experience currently working for this person?

That distinction is enormous.

A future accessibility agent might:

- detect cognitive overload
- reduce unnecessary complexity
- adapt information density
- alter interaction pacing
- provide multimodal explanations
- mediate stressful workflows
- reduce interruption burden
- simplify navigation paths
- maintain continuity across tasks
- summarise content dynamically
- support memory and orientation
- negotiate sensory preferences
- and personalise communication styles

Importantly, this could happen:

- continuously
- contextually
- and individually

rather than through static one-size-fits-all rules.

This may help address some of the structural biases embedded in traditional standards.

Because accessibility would become less dependent on universal assumptions.

---

# AI could help resolve conflicts between disability needs

One of the most promising possibilities of adaptive systems is the ability to support conflicting needs simultaneously.

For example:

A system might allow:

- one user to receive highly simplified summaries
- another to receive dense technical detail
- another to receive conversational guidance
- another to receive visual workflows
- another to suppress motion entirely
- another to preserve orientation animations

without requiring separate products.

This moves accessibility away from:

- universal defaults
- and toward negotiated experiences

In theory, adaptive systems could reduce some of the tensions between:

- simplicity and detail
- verbosity and brevity
- guidance and autonomy
- consistency and flexibility

This is potentially transformative.

Especially for neurodivergent accessibility.

---

# But agentic AI could also amplify bias dramatically

The optimistic vision is not guaranteed.

Agentic systems introduce entirely new risks.

In fact, they may reproduce accessibility inequities at far greater scale.

## Training data bias

If AI systems are trained primarily on dominant interaction patterns, they may:

- misinterpret disabled behaviour
- pathologise neurodivergent communication
- optimise for majority preferences
- suppress non-standard workflows
- or incorrectly “correct” user behaviour

## Behavioural normalisation

Adaptive systems may unintentionally push users toward:

- neurotypical interaction patterns
- socially normative communication styles
- conventional productivity expectations
- or mainstream comprehension models

This raises difficult ethical questions.

Is adaptation helping users?

Or subtly enforcing conformity?

## Invisible paternalism

An AI system that dynamically simplifies content may:

- remove important nuance
- make assumptions about cognitive ability
- infantilise users
- or limit autonomy

Especially if users cannot meaningfully control adaptation.

## Consent and transparency

If systems adapt based on:

- stress signals
- behaviour analysis
- eye tracking
- cognitive modelling
- emotional inference
- interaction history

then accessibility becomes entangled with:

- surveillance
- privacy
- autonomy
- and algorithmic power

Accessibility support that removes agency is not truly inclusive.

---

# Accessibility may shift from standards to relationships

Historically, accessibility has largely been:

- rules-based
- component-based
- standards-driven
- and interface-centric

Agentic systems may shift accessibility toward something more relational.

Instead of asking:

> Is this interface accessible?

we may increasingly ask:

> How effectively does this system understand and support this person over time?

That is a fundamentally different model.

It treats accessibility not as a static state.

But as an ongoing interaction.

This may particularly benefit:

- neurodivergent users
- people with fluctuating impairments
- users with mixed access needs
- people experiencing fatigue
- users under stress
- older adults
- and users whose accessibility barriers emerge contextually rather than consistently

Yet relational systems also create profound risks around:

- trust
- dependency
- behavioural manipulation
- power imbalance
- and algorithmic exclusion

---

# Accessibility professionals may need entirely new skills

If accessibility evolves toward adaptive experiential systems, the role of accessibility professionals may also change.

Future accessibility work may increasingly involve:

- inclusive AI governance
- adaptive interaction ethics
- cognitive accessibility modelling
- participatory AI design
- accessibility personalisation frameworks
- algorithmic transparency
- sensory and emotional experience design
- and disability-informed AI evaluation

This may require accessibility to move beyond:

- WCAG conformance alone
- static audits
- component checklists
- and purely technical remediation

toward:

- systems thinking
- human variability modelling
- behavioural ethics
- and continuous experiential evaluation

Accessibility maturity may eventually depend less on:

> “Can this organisation pass accessibility audits?”

and more on:

> “Can this organisation continuously adapt to diverse human needs without causing harm?”

---

# The most important question may not be technical

The future challenge may not simply be:

- whether AI can personalise accessibility
- or whether standards contain bias

The deeper question may be:

> Who gets to define what an accessible experience should feel like?

Historically, accessibility standards emerged from a combination of:

- disability advocacy
- technical feasibility
- institutional negotiation
- legal systems
- and industry compromise

Agentic AI could redistribute some of that power.

But redistribution is not inherently liberation.

If accessibility adaptation becomes controlled primarily by:

- platform vendors
- AI providers
- behavioural optimisation systems
- or commercial incentives

then accessibility risks becoming:

- opaque
- personalised without accountability
- and potentially manipulative

The challenge is therefore not only technical adaptation.

It is governance.

Participation.

Agency.

And power.

---

# Accessibility standards are still essential

Critiquing standards should not be mistaken for rejecting them.

WCAG, EN 301 549, and institutional guidance remain foundational.

Without them:

- many accessibility gains would never have occurred
- legal protections would weaken
- procurement leverage would diminish
- interoperability would degrade
- and accessibility investment would likely collapse in many organisations

The issue is not that standards failed.

It is that static standards may not be sufficient for modelling human diversity at experiential depth.

Especially as digital systems become:

- increasingly adaptive
- conversational
- predictive
- immersive
- and AI-mediated

Accessibility may therefore be entering a transition period.

From:

- standardised accessibility

Toward:

- adaptive inclusive systems.

---

# Final reflection

Accessibility standards changed the world.

They made digital exclusion visible.

They created accountability.

They established the principle that disabled people have a right to participate.

But they were also products of their time.

And like all systems, they reflect assumptions about:

- disability
- usability
- communication
- cognition
- productivity
- and what kinds of human experiences can be standardised

The rise of agentic AI may expose both the strengths and limitations of those assumptions.

For the first time, digital systems may be capable of adapting continuously to individual access needs rather than expecting individuals to adapt to fixed systems.

That possibility is extraordinary.

But it is also dangerous.

Because accessibility is not only about adaptation.

It is about dignity.

Autonomy.

Participation.

Trust.

And the right to define one’s own experience.

The future of accessibility may therefore depend not only on making systems more intelligent.

But on ensuring they remain deeply human.
