# Product Backlog

## Team Information

- Team name: [Team name]
- Project title: [Working project title]
- Primary user group for the first release: [One user group]
- Format: [User stories with one use case / Use cases with acceptance criteria]

| Member | GitHub username | Personal CSC181 repository |
|---|---|---|
| [Full name] | [Username] | [Repository link] |
| [Full name] | [Username] | [Repository link] |
| [Full name] | [Username] | [Repository link] |
| [Full name] | [Username] | [Repository link] |

<!-- Add rows for all members. -->

## 1. Interview Summary

[List the interviews or observations your team conducted. Use roles and codes,
not names or contact details. Include at least two stakeholder groups.]

| Code | Stakeholder role | Date | Method | Interviewer(s) |
|---|---|---|---|---|
| [V1] | [Role] | [YYYY-MM-DD] | [In person, call, chat, observation] | [Member name(s)] |
| [V2] | [Role] | [YYYY-MM-DD] | [Method] | [Member name(s)] |
| [O1] | [Role] | [YYYY-MM-DD] | [Method] | [Member name(s)] |

## 2. From Interview Notes to Needs

[Record at least 8 findings. Follow the worked example on Week 4, slide 10.
Type is F (functional), Q (quality / non-functional), or C (constraint).
See Week 4, slide 7.]

| ID | Source | What we heard or saw | Underlying need | Requirement idea | Type |
|---|---|---|---|---|---|
| F1 | [V1] | [Quote or observation] | [Need] | [What the software could do] | [F/Q/C] |
| F2 | [V2] | [Quote or observation] | [Need] | [Idea] | [F/Q/C] |
| F3 | [Source] | [Quote or observation] | [Need] | [Idea] | [F/Q/C] |
| F4 | [Source] | [Quote or observation] | [Need] | [Idea] | [F/Q/C] |
| F5 | [Source] | [Quote or observation] | [Need] | [Idea] | [F/Q/C] |
| F6 | [Source] | [Quote or observation] | [Need] | [Idea] | [F/Q/C] |
| F7 | [Source] | [Quote or observation] | [Need] | [Idea] | [F/Q/C] |
| F8 | [Source] | [Quote or observation] | [Need] | [Idea] | [F/Q/C] |

### Assumption log

[List things the team believes but has not confirmed. See Week 3, slide 19.]

| ID | Assumption | Risk if wrong (High/Medium/Low) | How we will check it |
|---|---|---|---|
| A1 | [Assumption] | [Risk] | [Check] |
| A2 | [Assumption] | [Risk] | [Check] |

## 3. User Stories

[Write 10 to 15 stories. Every story cites at least one finding ID. Mark the
INVEST check Yes only after the team has reviewed the story. See Week 4,
slides 14–17.]

| ID | User story | Source finding(s) | Epic | INVEST check |
|---|---|---|---|---|
| US-01 | As a [role], I want [goal], so that [benefit]. | [F1, F3] | [Epic name or none] | [Yes/No] |
| US-02 | As a [role], I want [goal], so that [benefit]. | [F2] | [Epic] | [Yes/No] |
| US-03 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |
| US-04 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |
| US-05 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |
| US-06 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |
| US-07 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |
| US-08 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |
| US-09 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |
| US-10 | As a [role], I want [goal], so that [benefit]. | [Finding IDs] | [Epic] | [Yes/No] |

### Epics and how we split them

[List each epic and the stories it was split into. Name the splitting approach:
by workflow step, by business rule, by data type, or happy path first.
See Week 4, slide 18.]

| Epic | Split into | How we split it |
|---|---|---|
| [Epic name] | [US-xx, US-xx, US-xx] | [Approach] |

### Stories we rewrote

[Give at least two examples of a story the team rewrote or split, and why.
See Week 4, slide 17.]

1. Before: [Original story]
   After: [Rewritten or split story or stories]
   Reason: [Which INVEST quality was missing]
2. Before: [Original story]
   After: [Rewritten story]
   Reason: [Reason]

## 4. Acceptance Criteria

[Write at least 3 specific, testable criteria for every story. Mark unhappy
paths with (unhappy). For Must-have stories, also write at least 2
Given–When–Then scenarios: one normal case and one unhappy path. Avoid weak
words (Week 4, slide 12). See Week 4, slides 20–21.]

### US-01: [Short story title]

Acceptance criteria:

- [ ] [Criterion 1]
- [ ] [Criterion 2]
- [ ] [Criterion 3 (unhappy)]

Scenario 1: [Normal case]

```gherkin
Given [starting state, with concrete values]
When [action]
Then [observable result]
```

Scenario 2: [Unhappy path]

```gherkin
Given [starting state]
When [action]
Then [observable result]
```

### US-02: [Short story title]

Acceptance criteria:

- [ ] [Criterion 1]
- [ ] [Criterion 2]
- [ ] [Criterion 3 (unhappy)]

<!-- Repeat for every story. Add Given–When–Then scenarios for Must-have stories. -->

## 5. Quality Requirements and Constraints (EARS)

[Write at least 3, using at least two different EARS patterns. Record who
agreed to any number. See Week 4, slides 7 and 13.]

| ID | Requirement | EARS pattern | Type | Source | Number agreed with |
|---|---|---|---|---|---|
| NFR-01 | [While the device is offline, the system shall …] | [State-driven] | [Quality/Constraint] | [F-ids] | [Stakeholder code or N/A] |
| NFR-02 | [When …, the system shall …] | [Event-driven] | [Type] | [F-ids] | [Code] |
| NFR-03 | [The system shall …] | [Ubiquitous] | [Type] | [F-ids] | [Code] |

## 6. Use Case

### Use-case diagram

[Show the system boundary, the actors, and the main use cases.
See Week 4, slide 23.]

<!-- ![Use-case diagram](backlog-images/use-case-diagram.png) -->

### UC-01: [Use case name]

[Choose the workflow with the most steps or error paths. See Week 4, slide 24.]

| Field | Description |
|---|---|
| Primary actor | [Role] |
| Precondition | [What must be true before it starts] |
| Main success scenario | 1. [Step] <br> 2. [Step] <br> 3. [Step] <br> 4. [Step] <br> 5. [Step] |
| Extensions | [2a. Condition: what the system does] <br> [4a. Condition: what the system does] |
| Postcondition | [What is true when it succeeds] |
| Stories covered | [US-xx, US-xx] |

## 7. Story Map

[Write the user's journey steps across the top and place story IDs under each
step, highest priority first. Release 1 must have a story under every step.
See Week 4, slide 19. You may embed an image instead.]

| | [Journey step 1] | [Journey step 2] | [Journey step 3] | [Journey step 4] |
|---|---|---|---|---|
| **Release 1 (MVP)** | [US-xx] | [US-xx] | [US-xx] | [US-xx] |
| **Release 2** | [US-xx] | [US-xx] | [US-xx] | [US-xx] |
| **Later** | [US-xx] | [US-xx] | [US-xx] | [US-xx] |

<!-- ![Story map](backlog-images/story-map.png) -->

## 8. The Ordered Backlog

[List every story in one order, highest priority first, with no ties. See Week 4, slides 26–28.]

| Rank | Story | MoSCoW | Size (S/M/L) | Value / effort quadrant | Sprint |
|---|---|---|---|---|---|
| 1 | [US-xx Title] | [Must] | [S] | [Quick win] | [Sprint 1] |
| 2 | [US-xx Title] | [Must] | [M] | [Big bet] | [Sprint 1] |
| 3 | [US-xx Title] | [Must] | [Size] | [Quadrant] | [Sprint] |
| 4 | [US-xx Title] | [Should] | [Size] | [Quadrant] | [Sprint 2] |
| 5 | [US-xx Title] | [Should] | [Size] | [Quadrant] | [Sprint] |
| 6 | [US-xx Title] | [Could] | [Size] | [Quadrant] | [Later] |
| 7 | [US-xx Title] | [Won't] | [Size] | [Quadrant] | [Not this time] |

### How we ordered it

[Explain in 3–5 sentences why the top stories are at the top. Mention value
to stakeholders, risk, and dependencies.]

### Capacity check

| Question | Answer |
|---|---|
| How many Must-have stories, and their total size? | [Number and sizes] |
| Do the Must-haves fit in about 60% of our time for two sprints? | [Yes/No, and why we think so] |
| Do the Release 1 stories form one complete path through the core workflow? | [Yes/No] |
| Are all L-sized Must-have stories split? | [Yes/No] |

## 9. Definition of Done

[List the conditions every story must meet before it counts as done, starting
in Sprint 1. See Week 4, slide 22.]

- [ ] [Condition 1]
- [ ] [Condition 2]
- [ ] [Condition 3]
- [ ] [Condition 4]

## 10. Traceability Table

[One row per Must-have story. See Week 4, slide 30. You will add test case IDs
in Week 9.]

| Story | Problem or goal it addresses | Source finding(s) | Test cases (Week 9) |
|---|---|---|---|
| [US-xx] | [Goal] | [F-ids] | [Leave blank for now] |
| [US-xx] | [Goal] | [F-ids] | [Leave blank for now] |
| [US-xx] | [Goal] | [F-ids] | [Leave blank for now] |

Gaps found: [Goals with no stories, or stories with no goal, and what we did
about them. Write None if there were none.]

## 11. Validation

### Team review

[Record at least two problems the team found using INVEST, the quality
checklist on Week 4, slide 11, and the common mistakes on slide 32.]

| Problem found | Story or requirement | How we fixed it |
|---|---|---|
| [Problem] | [ID] | [Fix] |
| [Problem] | [ID] | [Fix] |

### Stakeholder walk-through

[Show the story map and the top of the backlog to at least one stakeholder you
interviewed. See Week 4, slide 31.]

| Stakeholder | Date | What they said | What we changed |
|---|---|---|---|
| [Code and role] | [YYYY-MM-DD] | [Feedback] | [Change] |

## 12. Open Questions for Sprint 1

1. [Question 1]
2. [Question 2]
3. [Question 3]

## 13. Member Contribution Record

[Record actual contributions, including interviews, analysis, writing stories
and criteria, and reviewing.]

| Member | Interviews or analysis | Stories, criteria, or use case | Review or validation |
|---|---|---|---|
| [Name] | [Contribution] | [Contribution] | [Contribution] |
| [Name] | [Contribution] | [Contribution] | [Contribution] |

## 14. References

[List the lecture slides and external sources used. Write None if no external
sources were used.]

## 15. Team AI Use Declaration

Select one option:

- [ ] No generative AI tools were used by any member in preparing this submission.
- [ ] One or more members used generative AI tools. Details are provided below.

[If AI was used, complete the table. If not, write Not applicable.]

| Member who used AI | Tool | Purpose and sections assisted | How output was checked or revised |
|---|---|---|---|
| [Name] | [Tool] | [Purpose/sections] | [Review process] |

### Main prompts or interaction summary

[Provide the main prompts or a clear summary of the assistance received.
Write Not applicable if no AI tools were used.]

We acknowledge that AI-generated suggestions are not evidence of actual
stakeholder interviews, feedback, or verified user needs. Every finding in
Section 2 and every walk-through in Section 11 comes from a real person we
spoke to or observed. We remain responsible for the accuracy and
explainability of this submission.

## 16. Team Confirmation

We confirm that this document reflects our team's agreed-upon product backlog. All members
listed below reviewed the final version, and each member will upload the same
Markdown file to their personal CSC181 repository.

| Member | Reviewed final version |
|---|---|
| [Name] | [Yes/No] |
| [Name] | [Yes/No] |

## Submission Checklist

- [ ] Interviews cover at least two stakeholder groups, with sources coded and no personal information.
- [ ] The needs table has at least 8 findings, each labelled F, Q, or C.
- [ ] Assumptions are recorded separately from evidence.
- [ ] There are 10 to 15 user stories, each with a real role, a "so that", and at least one finding.
- [ ] Epics are split, and at least two rewrites are recorded.
- [ ] Every story has at least 3 acceptance criteria, including an unhappy path, with no weak words.
- [ ] Every Must-have story has at least 2 Given–When–Then scenarios.
- [ ] At least 3 quality requirements or constraints use EARS patterns.
- [ ] One use case has a diagram, a main success scenario, and at least 2 extensions.
- [ ] The story map has a Release 1 line that crosses every journey step.
- [ ] Every story has a MoSCoW label and a size, and the backlog is in one order with no ties.
- [ ] Must-haves fit in about 60% of capacity. Won't-have stories are kept, not deleted.
- [ ] A Definition of Done is included.
- [ ] The traceability table covers every Must-have story.
- [ ] The team review and the stakeholder walk-through are recorded.
- [ ] Contributions, references, and AI use are declared.
- [ ] All members reviewed the same final document.
- [ ] Each member saved the file as `activities/product-backlog.md`, with images in `activities/backlog-images/`.
- [ ] Each member committed and pushed their copy to their personal repository.
- [ ] Each member submitted their own GitHub file link through MOLE before November 9, 2026 23:59:59.
