# Trustworthy AI Enablement: AI RMF Learning Orientation

[← Back to README](README.md)

## Purpose

This page explains how the training uses the **NIST AI Risk Management Framework (AI RMF)** as a learning and risk-management orientation.

The purpose is not to reproduce the framework or teach learners to implement it as a formal organizational program.

Instead, the training uses the AI RMF vocabulary to help managers and decision makers develop a structured way to think about:

* context;
* risks;
* trustworthiness considerations;
* evidence;
* accountability;
* human oversight;
* risk responses;
* and ongoing monitoring.

The four AI RMF functions used as the organizing lens are:

> **GOVERN → MAP → MEASURE → MANAGE**

---

## Why Use an AI RMF-Informed Lens?

Managers responsible for AI adoption may encounter AI-related questions without having a technical background in AI development or risk management.

A structured vocabulary can help create a common language for conversations between:

* business leaders;
* operational teams;
* AI users;
* technical specialists;
* risk functions;
* and other stakeholders.

The learning design therefore uses AI RMF terminology as a bridge between **AI fluency and managerial decision making**.

The objective is not terminology mastery for its own sake.

The objective is to help learners ask better questions about AI-enabled work.

---

## The Four Functions

The AI RMF organizes its core around four functions:

```text id="1h4p7d"
                 GOVERN
                    │
          ┌─────────┼─────────┐
          │         │         │
         MAP     MEASURE    MANAGE
          │         │         │
          └─────────┼─────────┘
                    │
             Ongoing Risk
              Management
```

These functions should not be interpreted here as a simple linear process.

They provide different perspectives for considering AI risk throughout the lifecycle.

NIST describes **GOVERN, MAP, MEASURE, and MANAGE** as the four functions of the AI RMF Core. GOVERN is intended to be cross-cutting, while the other functions support understanding, evaluating, and responding to AI risks. ([NIST AI RMF 1.0](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf))

---

# GOVERN

## Learning Focus

**GOVERN** is introduced as the organizational dimension of responsible AI decision making.

Learners consider questions such as:

* Who has responsibility?
* Who has decision authority?
* What organizational expectations or policies apply?
* Where could accountability become unclear?
* Who should participate in the decision?
* How should responsibilities be communicated?

The learning experience uses these questions to help managers recognize that AI adoption is not solely a technology decision.

It can also create questions about **roles, responsibilities, accountability, and organizational expectations**.

---

## Scenario Application

In the accountability-gap scenario, for example, learners examine whether the presence of a human reviewer actually establishes meaningful responsibility.

The relevant question becomes:

> **Who is accountable for the decision, and does that person have the authority and ability to exercise meaningful judgment?**

This turns GOVERN into a practical learning lens rather than a definition to memorize.

---

# MAP

## Learning Focus

**MAP** is used to help learners understand the context in which an AI system or use case operates.

Learners consider:

* What is the intended purpose?
* What is the operating context?
* Who may be affected?
* What potential impacts should be considered?
* What assumptions are being made?
* What risks may be relevant to this particular use?

This is important because the same AI capability may present different considerations depending on **how, where, and by whom it is used**.

---

## Scenario Application

In the uneven-recommendation scenario, the learner cannot evaluate the situation simply by observing that the system produces different outcomes.

The learner first needs to understand:

* what the system is being used for;
* what decisions it supports;
* who may be affected;
* what the observed differences represent;
* and what potential consequences could follow.

This encourages **context-sensitive risk awareness**.

---

# MEASURE

## Learning Focus

**MEASURE** is introduced through questions about evidence and evaluation.

Learners consider:

* What do we know?
* What do we not know?
* What evidence is available?
* What characteristics or risks need to be evaluated?
* What should be monitored?
* What information would increase confidence in the proposed use?

The learning experience deliberately avoids implying that every AI use case requires the same metrics or evaluation methods.

The appropriate evidence depends on the system, context, intended use, risks, and organizational requirements.

---

## Scenario Application

In the GenAI scenario, the fact that users report productivity improvements does not by itself establish that the workflow is operating appropriately.

The learner may need to consider:

* the reliability of generated content;
* how frequently outputs are reviewed;
* what types of errors occur;
* how users respond to uncertain outputs;
* and whether actual use matches the intended workflow.

The learning objective is to develop the habit of **asking what evidence is needed before relying on a conclusion**.

---

# MANAGE

## Learning Focus

**MANAGE** is used to help learners consider what should happen when risks have been identified or uncertainty remains.

Learners consider:

* Which risks require attention?
* What response is appropriate?
* Should the proposed use continue?
* Should it be restricted?
* Is additional evidence needed?
* Should human oversight be strengthened?
* Should the decision be escalated or revisited?
* What should be monitored going forward?

The training does not prescribe a universal risk response.

Instead, learners examine how the response should reflect the **context, potential impact, available evidence, and organizational responsibilities**.

---

## Scenario Application

A learner may conclude that immediate expansion of an AI workflow is premature.

That does not necessarily mean rejecting the technology.

The appropriate response might instead involve:

* limiting the intended use;
* increasing human review;
* gathering additional evidence;
* clarifying accountability;
* establishing monitoring;
* or revisiting the decision after further evaluation.

This distinction is important to AI enablement.

**Responsible adoption is not equivalent to either unrestricted adoption or blanket rejection.**

---

# Connecting the Functions to Learning

The four functions provide different questions that can be brought into the same scenario.

| Function    | Learning question                                                                  |
| ----------- | ---------------------------------------------------------------------------------- |
| **GOVERN**  | Who is responsible, and what expectations or boundaries apply?                     |
| **MAP**     | What is the context, intended use, and potential impact?                           |
| **MEASURE** | What evidence or evaluation is needed?                                             |
| **MANAGE**  | What response is appropriate given the identified risks and available information? |

A single scenario may involve all four.

The learner is therefore not expected to assign a scenario to only one function.

---

# Example: Applying the Lens to a GenAI Workflow

Consider a department using Generative AI to support the preparation of customer-facing material.

The AI-generated drafts are useful, but employees increasingly rely on them without consistent verification.

A learner could examine the situation through the four functions:

### GOVERN

Who establishes the expectations for review and appropriate use?

Who remains accountable for the final material?

### MAP

What types of content are being generated?

Who could be affected by inaccurate or inappropriate output?

What is the intended role of GenAI in the workflow?

### MEASURE

What information would help determine whether the workflow is functioning as intended?

What should be monitored about output quality and actual user behavior?

### MANAGE

Should the workflow continue unchanged?

Should its use be restricted?

Should human review be strengthened?

Should additional evidence be gathered?

The value of the exercise is not selecting a particular function.

The value is **using the functions to structure better questions**.

---

# AI RMF and the AI Lifecycle

The learning experience connects the AI RMF-informed lens with an ongoing lifecycle perspective.

```text id="9z6k2w"
      DESIGN
        │
        ▼
    DEVELOP
        │
        ▼
    DEPLOY
        │
        ▼
       USE
        │
        ▼
    MONITOR
        │
        ▼
 REVIEW / ADAPT
        │
        └───────────────┐
                        ▼
                    CONTEXT
                    REVISITED
```

The purpose of this model is to reinforce that risk-management considerations can continue after deployment.

An AI-enabled workflow may change as:

* people begin using the system differently;
* reliance increases;
* new failure modes become visible;
* the operating environment changes;
* performance changes;
* or new impacts become apparent.

This supports the training objective of developing **ongoing risk awareness**.

---

# Trustworthiness and Trade-Offs

The AI RMF identifies multiple characteristics associated with trustworthy AI.

These include:

* validity and reliability;
* safety;
* security and resilience;
* accountability and transparency;
* explainability and interpretability;
* privacy enhancement;
* fairness with harmful bias managed.

The learning design does not treat these characteristics as a universal ranking.

Different contexts may create different priorities and tensions.

For example:

> Increasing automation may improve efficiency while increasing the importance of meaningful human oversight.

Or:

> Greater personalization may create value while raising additional questions about fairness or privacy.

The learner's task is therefore to recognize the **contextual trade-off**, not to memorize a preferred hierarchy.

---

# AI Fluency Through Risk Questions

The training uses AI fluency to mean more than familiarity with AI tools.

For this learning experience, AI fluency includes the ability to:

* recognize relevant AI capabilities and limitations;
* understand that outputs may require verification;
* recognize potential risk signals;
* ask appropriate questions about intended use;
* understand the importance of human responsibility;
* recognize when additional evidence may be required;
* establish reasonable boundaries;
* and participate constructively in AI-related decisions.

This is particularly relevant for managers who may be responsible for AI-enabled work without being responsible for developing the underlying AI system.

---

# What This Approach Does Not Do

The AI RMF is **not** presented as:

* a simple four-step checklist;
* a certification pathway;
* a substitute for specialist risk assessment;
* a technical AI testing methodology;
* a compliance framework;
* or a guarantee of trustworthy AI.

The training also does not imply that a manager can resolve every AI risk independently.

Some situations may require additional expertise from areas such as:

* technical evaluation;
* cybersecurity;
* privacy;
* legal and regulatory functions;
* data governance;
* safety;
* or organizational risk management.

The learning objective is to help managers **recognize when such considerations or expertise may be relevant**.

---

# Design Principle

The AI RMF-informed learning approach can be summarized as:

> **Use a recognized risk-management vocabulary to improve the questions decision makers ask about AI—not to turn a learning experience into a simplified governance checklist.**

This distinction keeps the training focused on AI enablement.

The learner is developing the ability to participate more effectively in responsible AI decisions rather than being trained as an AI risk specialist.

---

# Portfolio Evidence

This page demonstrates the ability to:

* work with established AI risk-management terminology;
* translate a formal framework into manager-oriented learning questions;
* distinguish framework concepts from instructional interpretation;
* connect AI risk awareness with AI fluency;
* integrate lifecycle thinking into learning design;
* connect governance, context, evidence, and risk response;
* communicate complex AI concepts without unnecessary technical language;
* maintain appropriate professional boundaries around expertise and claims.

The design intentionally demonstrates **applied understanding without claiming certification or formal implementation experience**.

---

## Reference Sources

* [NIST Artificial Intelligence Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
* [NIST AI RMF 1.0](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)
* [NIST AI RMF Playbook](https://www.nist.gov/itl/ai-risk-management-framework/nist-ai-rmf-playbook)
* [NIST AI RMF Core and Profiles](https://airc.nist.gov/airmf-resources/)

---

## Continue

* [← Scenario Design](03-scenario-design.md)
* [Next: Assessment Approach →](05-assessment-approach.md)
* [Example Learning Experience →](06-example-learning-experience.md)
* [Back to README →](README.md)
