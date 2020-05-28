# Change request

When there is a desire to change something about the products, processes or anything else, the first step is to open a change request in the [general repository](https://github.com/teamforus/general/issues). This makes it possible to:

* Rate the change request on subjects like; **priority**, **difficulty** and **scope** by adding [labels](https://github.com/teamforus/general/blob/develop/manuals/development/labels.md)
* Have a discussion about the request
* Keep track of the status of the change.

The goal of a change request is to either be closed (it is not needed, feasible or desired), or to evolve into an [improvement proposal](https://github.com/teamforus/general/blob/develop/manuals/development/issue-improvement-proposal.md).

## What makes a good change request?

While a change request can be created in any format, some things increase the chance that it will be actively worked on: 

### User story

The main function of a change request is to clearly state the desired change. A user story generally is a good format for this.

e.g. As a XXX I would like XXX so that XXX

Example: *As a user I would like to see a loading progress animation when I am waiting so that I know that I don't need to refresh the page.*

### Context
To help with deciding the priority it helps to give some context about why this change request was opened.

Example: *We have been getting a lot of calls lately that would be solved by implementing this change*

### Suggestions
A change request is not about proposing a solution, that would make it an [improvement proposal](https://github.com/teamforus/general/blob/develop/manuals/development/issue-improvement-proposal.md). But, it could still be helpful to add some suggestions to the change request.

## Turning a change request into an improvement proposal

The goal of a change request is to facilitate a desicion:
 
* This change will not be implemented (no-go); inform requester and close issue
* We will proceed and invest in making an improvement proposal (go)

If a go is given on the change request, it can be turned into an improvement proposal.

### How to turn a change request into an improvement proposal.

There are generally two options when converting a change request into an improvement proposal:

If the issue and comment section are still small, the original change request can be put in an expandable block, and work on the improvement proposal can continue in the original issue.

<details><summary>Click to view change request</summary>
The original change request.
</details>

If the change request has become very big, it might be better to:

* Open a new issue for the improvement proposal
* Add a link to the change request to the new improvement proposal
* Close the change request, and comment "this change request has been turned into an improvement proposal: [add link]()"

# [Start you making your change request](https://github.com/teamforus/general/issues/new?assignees=maxvisser&labels=Approval%3A+Not+requested%2C+Status%3A+Not+Planned%2C+Type%3A+Change+request&template=change-request.md)

