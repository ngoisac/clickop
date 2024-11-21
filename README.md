```mermaid
---
title: Member indoctrination pipeline 
---

flowchart TD
  A -> B
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
  
