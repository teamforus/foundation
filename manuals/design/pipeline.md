# Design Manual: Pipeline
This manual explains both how you can work on something new or do an experiment, and also how to get it into the final product.

## Figma
Figma is a product design tool that enables real-time collaboration. Everybody can work on the same file, seeing what other people are doing. It works similair to google docs.

Figma can also be used to create prototypes that feel similair to the end product. A prototype can be easily shared and opened in the browser, enabeling people to post comments to give feedback.

Figma can be used in any modern browser. If you're a power-user it is recomended that you [download the desktop application](https://www.figma.com/downloads/) You don't need a subscription to start using it. 

Figma has great [documentation and tutorials](https://help.figma.com/hc/en-us) available for free.

## File locations
If you are part of the Forus team, you will have acces to these projects. If you are not part of the team, understanding these projects will still help you understand how our workflow is structured. Watch the [figma structure video](https://youtu.be/XR7DBatobQM) and/or the table below:

Directory | Purpose
-- | --
Drafts | Your personal space. By default only you see what is in here. You can choose to share a file using the "share" menu.
Inbox | Any (new) file can go here. If you're not sure where to put something, put it in the inbox.
General | Most other directories are meant for our products. The general directory is meant for all other files.
Proposals | Suggestions for improvements. Can be connected to an [improvement proposal](https://github.com/teamforus/general/blob/develop/manuals/development/issue-improvement-proposal.md) issue. 
Prototypes | Accepted proposals. Needs design and content. Can be linked to an [epic](https://github.com/teamforus/general/blob/develop/manuals/development/issue-epic.md) issue.
Pull requests | Final designs, handed off to developers. Should be merged into the library. Can be moved to the archive when merged into the library and deployments. Can be linked to one or more [task](https://github.com/teamforus/general/blob/develop/manuals/development/issue-task.md) issues 
Libraries | Design sources. Does not contain data. The library is organized based on the principles of atomic design. The library contains templates for the pages that are used in the deployments. 
Deployments | Here the templates are combined into a prototype that closely resembles the product currently in production and is filled with content. The deployements can be used for collecting feedback, taking screenshots, making training materials etc.
Archive | Move any files here that are not actively worked on, but should not be deleted.

## Core concepts

Figma components: https://youtu.be/HJJFD9gxGbY

#### Atomic design
Our library is organised based on the principles of [atomic design](http://atomicdesign.bradfrost.com/chapter-2/). 

Page | Description
---|---
[Atoms](http://atomicdesign.bradfrost.com/chapter-2/#atoms) | Basic HTML elements like form labels, inputs, buttons, and others that can’t be broken down any further without ceasing to be functional.
[Molecules](http://atomicdesign.bradfrost.com/chapter-2/#molecules) | Molecules are relatively simple groups of UI elements functioning together as a unit. For example, a form label, search input, and button can join together to create a search form molecule.
[Organisms](http://atomicdesign.bradfrost.com/chapter-2/#organisms) | Relatively complex UI components composed of groups of molecules and/or atoms and/or other organisms. These organisms form distinct sections of an interface.
[Templates](http://atomicdesign.bradfrost.com/chapter-2/#templates) | Templates are page-level objects that place components into a layout and articulate the design’s underlying content structure.

## Cloning a file
All files live in Figma. This means files don't have to be emailed around, and that there is no folder clutter on many different computers/clouds with many different versions. 

There simply is one "single source of truth". The master file is in Figma and can be accessed and edited (if you have the rights) trough one URL.

In figma, a file lives in an organisation project, or in your personal drafts. It is possible to clone a file from an organisation to your own drafts if the owner has enabled this.

<img width="406" alt="Screenshot 2020-01-28 at 11 09 39" src="https://user-images.githubusercontent.com/30194799/73254537-e46a8800-41be-11ea-89e1-c8855f136ea0.png">







