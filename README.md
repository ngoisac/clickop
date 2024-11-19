```mermaid
---
title: Member indoctrination pipeline 
---

flowchart TD
  Lead -->|Vetted| Candidate
  Lead -->|Rejected| Sorry
  Lead -->|Lost| Sorry
  Candidate -->|Application| Applicant
  Applicant -->|Payment+Approval| Onboarding( 
    Member Onboarding

  )
  Onboarding --> Slack
  Slack -->|Invite| Channels
  Slack --> Introduction

  Onboarding --> Member
  Member --> Trainings
```
  