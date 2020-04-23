## Context
In order to keep overview over all the issues in different repositories, clear labeling is critical. We expect each issue to have at least three labels: Status, Type and Priority. For administrative purposes, a project label can be added as well. 

## Priority
label | color | description
-- | -- | --
Priority: Critical - Hotfix | Color: #E00A00 | Show-stopping issue, forcing other work to pause until this is fixed. Should be released asap.
Priority: Critical - Next release | Color: #B93933 | Extremely important issue that should be fixed and tested before the next release window.
Priority: Must have | Color: #EFB23F | Requirements labelled as Must have are critical to the current sprint in order for it to be a succes.
Priority: Should have | Color: #39a4b2 | Important but not necessary for delivery in the current sprint.
Priority: Could have | Color: #327183 | Desirable but not necessary. Could improve the user experience or customer satisfaction.
Priority: Won't have | Color: #FCECA3 | Has been agreed by stakeholders as the least-critical, lowest-payback items, or not appropriate at. 

## Difficulty
label | color | description
-- | -- | --
Difficulty: Easy | Color: #27b376 | Most people should be able to pick this up.
Difficulty: Medium | Color: #f9a73e | Some experience required.
Difficulty: Hard | Color: #bf212f | Considerable experience required.

## Scope
label | color | description
-- | -- | --
Scope: Small | Color: #27b376 | Takes little time to do.
Scope: Medium | Color: #006f3c | Takes medium amount of time to do.
Scope: Big | Color: #f9a73e | Takes a lot of time to do
Scope: Too Big (should split) | Color: #bf212f | Takes an undesired time to do, should be split up.

## Status
label | color |  description
-- | -- | --
Status: Planned | Color: # | Added to planning
Status: Not Planned | Color: # | Not planned to be worked on
Status: In progress | Color: # | Is currently being worked on
Status: On hold | Color: # | Decision made to pause work
Status: Blocked | Color: # | Can not be worked on
Status: Needs review | Color: # | Should be reviewed
Status: No go | Color: # | Can not move on to next phase
Status: Go | Color: # | Can move on to next phase

## Approval
label | color |  description
-- | -- | --
Approval: Not requested | Color: #| Does not need to be approved at this time
Approval: Requested | Color: #| Should be reviewed for approval
Approval: Not granted | Color: #| Can not (yet) move on to the next phase
Approval: Granted | Color: #| Can move on to next phase

## Phase (Change Requests)
label | color |  description
-- | -- | --
Phase 1: Analysis | Color: # | Research if this change is desirable/feasable & what the impact would be.
Phase 2: Proposal | Color: # | Make a concrete proposal for the change.
Phase 3: Prototyping | Color: # | Create high fidelity prototype for approval and developer handoff.
Phase 4: Development | Color: # | Convert the prototype into code and add changes into the design library.
Phase 5: Staging | Color: # | Add the new feature to an upcoming release and merge the changes into the design library.
Phase 6: Testing | Color: # | Ensure that the new feature is stable and does not break anything.
Phase 7: Release | Color: # | Add the feature into production and inform users

## Type
label | color | description
-- | -- | --
Type: Bug | Color: #B93933 | Some functionality is broken or doesn't work as excpected
Type: Enhancement | Color: # | Improves excisting functionality
Type: Maintainance | Color: # | Released and currently available to end users
Type: Question | Color: # | Something that needs clearification or a decision
Type: Epic | Color: # | A collection of smaller issues
Type: RFC | Color: # | A request for commments, an idea of proposal that needs feedback
Type: Timetracking | Color: #333333 | Issue purely meant for timetracking, no action expected

## Projects
label | color | description
-- | -- | --
project-xx | Color: # | Project number for administrative purposes

## Topics
label | color | description
-- | -- | --
Topic: xx | Color: # | Topic, mostly for administrative purposes
Topic: Android | Color: #a5c736 | Android issues
Topic: iOS | Color: #a2abba | iOS issues
Topic: Frontend | Color: #08ce89 | Frontend issues: AngularJS, Gulp or other tasks related to forus-frontend repository.
Topic: Backend | Color: #f44e39 | Backend issues: related to Laravel or other tasks from forus-backend
Topic: MIT | Color: #bfd4f2 | MIT subsidary

Inspired by: https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63
