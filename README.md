The Try Again License

The Try Again License is a field-of-use license for AI systems, agent frameworks, constraint-governance methods, and autonomous execution workflows.

Its core principle is simple:

If “try again” is an acceptable recovery strategy, Community use likely applies.
If “try again” is not an acceptable recovery strategy, Commercial use likely applies.

Some AI systems can safely fail, retry, regenerate, rerun, or roll back. Others cannot. A bad blog post can be rewritten. A bad image can be regenerated. A buggy code PR can be reviewed and fixed.

But some mistakes are not safely recoverable through “try again.”

A wrong payment can move real money.
A wrong trade can create financial loss.
A wrong healthcare action can affect a patient.
A wrong drone action can hit the physical world.
A wrong compliance or legal action can create liability.

The Try Again License exists to draw that boundary.

License categories

The license defines three categories of use.

1. Community Use

Community Use is free for low-consequence, retry-safe systems.

Examples include:

* Blog generation
* Marketing content
* SEO / SEM content
* Image generation
* Video generation
* Graphic / UX design
* Market research
* Internal tooling
* Coding agents
* Low-risk SaaS development
* Educational use
* Non-commercial research
* Internal prototypes

The general rule:

If mistakes are cheap, reversible, and retry-safe, Community Use likely applies.

2. Growth / Limited Commercial Use

Growth / Limited Commercial Use applies to systems that may be low-risk at small scale but become more consequential as usage, revenue, customer exposure, or operational dependency increases.

Examples include:

* AI chief of staff systems
* Customer-facing agents below scale thresholds
* Voice agents below scale thresholds
* Appointment-setting agents below scale thresholds
* Admin assistants
* Recruitment workflows
* Executive search
* Corporate training
* Business process automation with human approval
* SaaS products using the protected material internally but not controlling high-consequence workflows

A commercial license may be required after certain thresholds, such as revenue, transaction volume, autonomous interactions, or operational dependency.

3. Full Commercial Use

Full Commercial Use requires a separate commercial license from day one.

Examples include:

* Payments
* Money movement
* Stablecoin movement
* Trading
* Wealth management
* Payroll and compliance
* KYC / AML
* Insurance claims
* Healthcare decision systems
* Clinical decision support
* Legal execution systems
* Supply chain and procurement
* Critical infrastructure
* Drones
* Robotics
* Autonomous vehicles
* Military or defense systems
* AGI systems
* Superintelligence systems

The general rule:

If failure could reasonably cause financial loss, legal exposure, medical harm, physical harm, regulatory violation, material operational disruption, reputational harm at scale, military consequences, institutional harm, or large-scale societal consequences, a commercial license is required.

Reversible vs. irreversible actions

The license also distinguishes between reversible and irreversible actions.

A reversible action is a two-way door. A mistake can be undone, regenerated, corrected, rolled back, ignored, or retried without material harm.

An irreversible action is a one-way door. A mistake cannot be safely undone through a simple retry, or reversal would create meaningful cost, risk, delay, harm, liability, or operational disruption.

Community Use generally applies to two-way door systems.

Commercial licensing generally applies to one-way door systems.

Protected material

The Try Again License is intended to cover the broader constraint-governance stack, including:

* AISpec
* WBS, meaning What-Boundaries-Success
* Bora’s Law
* Natural Boundary Theory
* Constraint Engineering
* Constraint Governance
* Constraint-Based Transfer Learning
* Constraint Graphs
* Constraint Backpropagation
* Functional Role Decomposition
* Reversible / irreversible action classification
* One-way door / two-way door governance
* Approval-gated autonomous execution
* AI Chief of Staff systems
* Drift measurement
* Constraint clarity scoring
* Delta clarity measurement
* Agent memory structures
* Approval frameworks
* Verification workflows
* Related software, documentation, templates, and derivative implementations

Important note

This license is not an open-source license as defined by the Open Source Initiative because it restricts certain commercial, field-specific, and high-consequence uses.

This repository is a public working version of the license and related examples. It should be reviewed by qualified legal counsel before use in high-consequence, commercial, regulated, or legally sensitive contexts.

Files

* LICENSE.md — full license text
* examples.md — example use cases and likely license category
* commercial-use.md — when a commercial license is required
* faq.md — common questions
