---
name: Change lifecycle template
about: Template for keeping track of a change
title: Change lifecycle [title]
labels: 'Priority: Low'
assignees: 'jamalv'

---

## Change

Requested by: @requester

### Change description

*example: As a sponsor I would like to xxx so that I can xxx


*/////////////////// leave below blank if unsure ///////////////////*

## Change livecycle.
Every change goes trough this lifecycle to ensure the highest quality result.

Phase 1: Analysis
Phase 2: Proposal
Phase 3: Prototyping
Phase 4: Development
Phase 5: Staging
Phase 6: Testing
Phase 7: Release

## Who does what? (RACI)
R = Responsible 
Those who do the work to complete the task

A = Accountable (Also Approver)
The one ultimately answerable for the correct and thorough completion of the deliverable or task, the one who ensures the prerequisites of the task are met and who delegates the work to those responsible. (can only be one person)

C = Consulted
Those whose opinions are sought, typically subject matter experts; and with whom there is two-way communication

I = Informed
Those who are kept up-to-date on progress, often only on completion of the task or deliverable; and with whom there is just one-way communication.

R: @username
A: @username
C: @username
I: @username

## Phase 1: Improvement Proposal

### User Story
As a << type of user: sponsor, provider, requester or validator >>
I want to << perform some task >>
So that I can << achieve some goal >>

### Acceptance criteria

Given << some context >>
When << some action is carried out>>
Then << a set of observable outcomes should occur >>

Make decision
- [ ] Go
- [ ] No Go

## Phase 2: Analysis

### Research feasibility

Effort, does change need planning and strategy or is it a quick win.

### Impact assessment

who will benefit from change; how many users;

## Risk assessment
This change would impact:
- [ ] Design
- [ ] Code
- [ ] Infrastructure
- [ ] Users
- [ ] Finances
- [ ] Processes

Make decision
- [ ] Go
- [ ] No Go

## Phase 3: Optional: Wireframe 
- [ ] plan a brainstorm session
   - [ ] results in a photo of a whiteboard, picture of a drawing on paper

- [ ] R has ask C for feedback or to join brainstorm session
- [ ] R asks A to approve wireframe
- [ ] R informs I of wireframe if done

Make decision
- [ ] Go
- [ ] No Go

## Phase 4: Mockup / Template
- [ ] create a fast mockup template with current library
  - [ ] design new elements if needed for template
- [ ] make a pr, ask designer to look at pr, the new template

- [ ] R ask C for feedback
- [ ] R asks A to approve template
- [ ] R informs I of wireframe if done

Make decision
- [ ] Go
- [ ] No Go

## Phase 5: Prototype
- [ ] Use templates to create a prototype in figma

- [ ] R ask C for feedback on prototype
- [ ] R asks A to approve prototype
- [ ] R informs I of prototype if done

Make decision
- [ ] Go
- [ ] No Go

## Phase 6: Development
Goal: Convert the prototype into code and add changes into the design library.

(draft) Pull request link: 

- [ ] Create a new feature branch and open draft pull request
- [ ] Create pull request file in figma and prepare new versions for library
- [ ] Review pull requests

Make decision
- [ ] Go
- [ ] No Go

## Phase 7: Staging
Goal: Add the new feature to an upcoming release and merge the changes into the design library

Release pull request link: 

- [ ] Merge into release branch and add to staging environment
- [ ] Communication plan of new release

## Phase 8: Testing
Goal: Ensure that the new feature is stable and does not break anything

- [ ] Run tests on staging environment
- [ ] Fix bugs if needed
- [ ] Revert merge if bugs not fixable for this release

## Phase 9: Release
Goal: Add the feature into production and inform users as planned in phase 2

- [ ] Inform users of (upcoming) change
- [ ] Release feature on a monday morning




