---
title        : API Threat Modeling Cheat Sheet
type         : outcome
track        :
video        :                    #url i.e. youtube, vimeo, etc
slides       :                    #url i.e. slideshare
images       :
session_type : user-session    # working-session, user-session, product-sesssion
technology   :
categories   : Threat Model
status       : done
description  :
---

## Outcomes
Three Cheat Sheets for central questions 2 to 4

## Synopsis and  Takeaways

The OWASP Threat Model Project seeks to document threat modeling techniques grouped around four key questions that form the basis of most TM methodologies:

- What are we building?
- What can go wrong?
- What are we going to do about that?
- Did we do a good enough job?

### Cheat Sheet Structure & Process

- Each cheat sheet has a maximum of five key points
- Each key point is as simple and concise as possible
- Each point starts with either DO or DON’T
- Ideas are collected in a collaborative environment
- The top five are chosen by consensus to be documented

### References
Cheat Sheet created for Question 1 at 2017 Summit

## Working Materials

#### Question 1: What are we building?

**DO**:
- Scope to what is under your control.
- Understand the context your system will live in. This includes but is not limited to the environment, security controls, etc
- If you get stuck, either look at the entry and exit points OR let the Subject Matter Expert (SME) tell a story to get back on track.

**DON’T**:
- Go beyond/deeper than design level.
- Use Threat Modeling like a kitchen sink, don’t try to put everything in.

### !Q1{{< img src="https://user-images.githubusercontent.com/39884432/41194889-2c6d9e80-6c23-11e8-8bac-88235c5423cd.jpg" width="720px" >}}



### Question Two: WHAT CAN GO WRONG?

**DO**:
- Use the whole team: including security operations, product owner, marketing and design usability (don’t limit yourself or shut down the brainstorm too early)
- Use existing libraries, practices and structures such as STRIDE, CAPEC, Kill Chain, Story Mapping (don’t reinvent the wheel)
- Capture good notes, use open questions, and own the follow-up process
- Engage constructively and blamelessly - create a safe space

**DON’T**:
- Get stuck in a framework, or discredit ideas because they don’t fit the framework (do admit when you are stuck and be wary of diminishing returns)

### !Q2 what can go wrong
{{< img src="https://user-images.githubusercontent.com/39884432/41194977-14b4d3f6-6c25-11e8-8458-2c6747bd266c.jpg" width="720px" >}}

### !Q2 graphic
{{< img src="https://user-images.githubusercontent.com/39884432/41194945-372503ee-6c24-11e8-99f8-89847d3efd46.jpg" width="720px" >}}

### Question Three: WHAT ARE WE GOING TO DO ABOUT IT?

**DO**:
- Collaborate, validate and prioritise (findings, threats and first assumptions)
- Draw on, extend and customise existing countermeasures
  - Organisational standards - SSO and WAF
  - Common standards - USE ACL and Hash PW
- Write tests and test cases
- Integrate with partner or team tools and processes

**DON’T**:
- Confuse can and should

###  !Q3 what can we do
{{< img src="https://user-images.githubusercontent.com/39884432/41195029-2aee353a-6c26-11e8-995a-247bbfe62865.jpg" width="720px" >}}

### !Q3
{{< img src="https://user-images.githubusercontent.com/39884432/41195031-3b61ad3e-6c26-11e8-92ee-268e15de0a7b.jpg" width="720px" >}}


### Question Four: DID WE DO A GOOD ENOUGH JOB?

**DON’T**:
- Skip this step!

**DO**:
- Follow Up and Actionable Outputs
- Follow up with Survey and Lessons Learned
- Keep what works and lose what fails
- Actioned Items
- Continuous Validation
- Compare Q1 (what we are building) with Q3 (what we built)
- Validate Assumptions
- Compare outputs with Bug Bounty, Pen Test and Audit Findings
- Share outputs with whole team

### !Q4 did we do a good job
{{< img src="https://user-images.githubusercontent.com/39884432/41195046-80e7b3b2-6c26-11e8-8964-be83aff3f56d.jpg" width="720px" >}}

## References

- **Session page :** [Threat Model Cheat Sheets](https://open-security-summit.org/tracks/threat-model/working-sessions/tm-cheatsheets/)

{{< img src="url" width="size" >}}
- **Summit 2017 session page :** [2017 Threat Model Sessions](https://owaspsummit.org/Working-Sessions/Threat-Model/index.html)

{{< img src="url" width="size" >}}

- **Summit 2017 outcome page :** [Outcomes OWASP Projects: Cheat Sheets](https://owaspsummit.org/Outcomes/Owasp-Projects/Cheatsheets.html)

{{< img src="url" width="size" >}}

### Additional/External References
OSWASP Cheat Sheet Guidelines: https://www.owasp.org/index.php/OWASP_Cheat_Sheet_Series#tab=Cheat_sheet_Guideline
