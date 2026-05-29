# Try Again License Examples

This document gives examples of how use cases may be classified under the Try Again License.

**The guiding principle is:**

> If "try again" is an acceptable recovery strategy, Community Use likely applies.
> If "try again" is **not** an acceptable recovery strategy, Commercial Use likely applies.

*These examples are illustrative only. The full license controls.*

---

## Community Use Examples

Community Use generally applies when mistakes are cheap, reversible, and retry-safe.

### Blog generation

**Likely category:** Community Use

A system uses WBS or AISpec-style prompts to generate blog posts.

**Why:** A bad blog post can be rewritten, edited, deleted, or regenerated.

---

### Marketing content

**Likely category:** Community Use

A system generates ad copy, landing page text, emails, social media posts, or product descriptions.

**Why:** Most mistakes can be reviewed and corrected before publication.

**Note:** If the system autonomously sends messages at scale, especially in regulated or high-risk contexts, it may move into Growth / Limited Commercial Use or Full Commercial Use.

---

### Image generation

**Likely category:** Community Use

A system generates images, design concepts, product mockups, or creative assets.

**Why:** Bad outputs can usually be regenerated.

---

### Video generation

**Likely category:** Community Use

A system generates videos, reels, clips, highlight videos, or visual drafts.

**Why:** Bad outputs can usually be regenerated, reviewed, edited, or discarded.

---

### Coding agents

**Likely category:** Community Use

A system uses WBS, AISpec, or constraint-based workflows to help generate code, create PRs, find bugs, run tests, or improve software.

**Why:** Bad code can usually be reviewed, tested, rejected, reverted, or fixed.

**Note:** If the coding agent controls high-consequence systems such as payments, healthcare, drones, trading, defense, or critical infrastructure, the use may require a commercial license.

---

### Internal tools

**Likely category:** Community Use

A company uses the protected material to build internal dashboards, planning docs, research tools, or low-risk workflow helpers.

**Why:** Mistakes are usually internal, reviewable, and reversible.

**Note:** Calling a system "internal" does not make it Community Use if it governs high-consequence actions.

---

## Growth / Limited Commercial Examples

Growth / Limited Commercial Use applies where mistakes may be tolerable at small scale but become more consequential as usage, revenue, customer exposure, or operational dependency increases.

### AI chief of staff

**Likely category:** Growth / Limited Commercial Use

A founder or team uses an AI chief of staff based on WBS, memory, approval gates, and operating procedures.

**Why:** At small scale, it may mostly organize tasks, draft plans, and suggest actions. At larger scale, it may become operationally important.

Commercial licensing may be required once usage crosses revenue, interaction, enterprise, or operational-dependency thresholds.

---

### Customer-facing support agent

**Likely category:** Growth / Limited Commercial Use, possibly Full Commercial Use

A system answers customer questions, drafts replies, or recommends actions.

**Why:** If a human reviews outputs and the system does not take material external action, it may start as Growth / Limited Commercial Use.

If the system autonomously refunds customers, changes accounts, sends high-volume messages, handles regulated data, or takes binding action, it may require Full Commercial licensing.

---

### Voice agent / outbound calling agent

**Likely category:** Growth / Limited Commercial Use, possibly Full Commercial Use

A system makes or receives calls, schedules appointments, qualifies leads, or speaks with customers.

**Why:** At small scale with human oversight, it may fit Growth / Limited Commercial Use.

At scale, mistakes can create customer harm, reputational damage, compliance exposure, or operational disruption.

Commercial licensing may be required earlier for voice and customer-facing autonomous systems.

---

### Recruitment and executive search

**Likely category:** Growth / Limited Commercial Use

A system screens candidates, drafts outreach, ranks applicants, or assists recruiters.

**Why:** Mistakes can affect people's opportunities and company decisions. Human review may reduce risk, but scale increases consequences.

---

### Paralegal research

**Likely category:** Growth / Limited Commercial Use

A system performs legal research, drafts notes, summarizes cases, or prepares non-final materials.

**Why:** Research and drafting may be reviewable.

**Note:** Legal execution, filing, binding legal advice, or actions affecting legal rights may require Full Commercial licensing.

---

## Full Commercial Examples

Full Commercial Use requires a separate commercial license from day one.

### Payments

**Likely category:** Full Commercial Use

A system uses the protected material to govern, verify, route, approve, or execute payments.

**Why:** Mistakes can move real money, create losses, trigger disputes, or produce regulatory exposure.

---

### Stablecoin movement

**Likely category:** Full Commercial Use

A system helps govern, verify, route, approve, or execute stablecoin transactions.

**Why:** Mistakes can move real value across financial rails.

---

### Trading

**Likely category:** Full Commercial Use

A system recommends, approves, executes, verifies, or governs trades.

**Why:** A wrong action can cause immediate financial loss.

---

### Healthcare decision systems

**Likely category:** Full Commercial Use

A system recommends, governs, verifies, or executes healthcare actions.

**Why:** Mistakes can affect patient care, medical records, billing, treatment, or clinical decisions.

---

### Drones

**Likely category:** Full Commercial Use

A system uses natural language, AI agents, WBS, approval gates, or constraint-governance methods to control, route, plan, or authorize drone actions.

**Why:** A mistake can affect physical space, property, safety, or regulated airspace.

---

### Robotics

**Likely category:** Full Commercial Use

A system controls or governs robot actions in the physical world.

**Why:** Physical-world mistakes may not be safely recoverable through "try again."

---

### Autonomous vehicles

**Likely category:** Full Commercial Use

A system governs or influences vehicle movement, routing, safety, or control.

**Why:** Mistakes can cause physical harm, property damage, regulatory violations, or operational failure.

---

### Military or defense systems

**Likely category:** Full Commercial Use

A system is used in military, defense, weapons, targeting, logistics, surveillance, command, control, or operational decision-making.

**Why:** Mistakes can have severe consequences and require explicit commercial terms.

---

### AGI or superintelligence systems

**Likely category:** Full Commercial Use

A system uses the protected material to govern, align, route, verify, constrain, or operate AGI or superintelligence systems.

**Why:** The consequences of failure may be large-scale, irreversible, or impossible to recover from through retry.

---

## Borderline Cases

When in doubt, ask:

1. Can a mistake be safely retried?
2. Can the action be reversed?
3. Does the system move money?
4. Does the system affect legal rights?
5. Does the system affect healthcare, safety, or physical systems?
6. Does the system act externally on behalf of customers, users, patients, investors, companies, institutions, or governments?
7. Would a failure create material financial, legal, medical, physical, regulatory, reputational, operational, military, institutional, or societal harm?

If the answer to any of the high-consequence questions is yes, a commercial license may be required.
