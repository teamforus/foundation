# Design
This manual explains both how you can work on something new or do an experiment, and also how to get it into the final product.

## Figma
Figma is a product design tool that enables real-time collaboration. Everybody can work on the same file, seeing what other people are doing. It works similair to google docs.

Figma can also be used to create prototypes that feel similair to the end product. A prototype can be easily shared and opened in the browser, enabeling people to post comments to give feedback.

Figma can be used in any modern browser. If you're a power-user it is recomended that you [download the desktop application](https://www.figma.com/downloads/) You don't need a subscription to start using it. 

Figma has great [documentation and tutorials](https://help.figma.com/hc/en-us) available for free.

## File locations
If you are part of the Forus team, you will have acces to these projects. If you are not part of the team, understanding these projects will still help you understand how our workflow is structured.

Project | Purpose
-- | --
Inbox | There are no rules here, anything can live in the inbox.
Prototypes | The files here are an experiment, they could either go to the final product or move to the archive.
Pull requests | When a prototype is approved for development, it will move to the pull requests project. Here it will be merged into the library while development is ongoing.
Libraries | The library is organized based on the principles of atomic design. The library contains templates for the pages that are used in production. 
Deployments | Here the templates are combined into a prototype that closely resembles the product currently in production. The deployements can be used for collecting feedback, taking screenshots, making training materials etc.
Archive | Here files are moved that are not planned tot be worked on in the near term.



## Essential Files

### [Library](https://www.figma.com/file/lmtX6abfCnGR9Ohep4TeI6/Library?node-id=15%3A0)
This is the heart of our design system. All the master components live in the library. The library is always leading. We  always aim to keep the codebase synchronized with the state of the library.

Only a few people can write to the library. Therefore, if you want to make changes to the library, you should first [clone](https://github.com/teamforus/development/blob/master/briefings/how-to-design.md#cloning-a-file) it, make the changes and then open a [pull request](https://github.com/teamforus/development/blob/master/briefings/how-to-design.md#pull-requests).

#### Pages
Our library is organised based on the principles of [atomic design](http://atomicdesign.bradfrost.com/chapter-2/). 

Page | Description
---|---
[Atoms](http://atomicdesign.bradfrost.com/chapter-2/#atoms) | Basic HTML elements like form labels, inputs, buttons, and others that can’t be broken down any further without ceasing to be functional.
[Molecules](http://atomicdesign.bradfrost.com/chapter-2/#molecules) | Molecules are relatively simple groups of UI elements functioning together as a unit. For example, a form label, search input, and button can join together to create a search form molecule.
[Organisms](http://atomicdesign.bradfrost.com/chapter-2/#organisms) | Relatively complex UI components composed of groups of molecules and/or atoms and/or other organisms. These organisms form distinct sections of an interface.
[Templates](http://atomicdesign.bradfrost.com/chapter-2/#templates) | Templates are page-level objects that place components into a layout and articulate the design’s underlying content structure.

### [Prototypes](https://www.figma.com/file/HL0xnMAHK9GtM9sWEK2rUM/Prototypes?node-id=14%3A647)
This is where designs come alive. Templates are filled with content and linked together to create prototypes. This is a seperate file that does not cointain master components, they are in the library. In this file only instances of templates are used, they are filled with content using [google sheet sync]().

The prototypes provide a good starting point for experimentation. You can copy the prototype, and detach instances that you would like to edit.

#### Pages
This file has one example and pages for the master prototypes. If you want to do an experiment or have a seperate usecase, you should clone this file.

Page | Description
---|---
Example | The example shows what a prototype can look like. Copy the example to make your own prototype.
Prototype/Me/iOS | Main prototype of the me app for iOS
Prototype/Me/iOS/lab | Lab version of the me app for iOS
Prototype/Me/Android | Main prototype of the me app for Android
Prototype/Forus/Dashboard | Main prototype of the dashboard Forus
Prototype/Forus/Webshop/Common | Main prototype of the common webshop
Prototype/Forus/Webshop/Implementation/Potjeswijzer | Webshop implementation of the potjeswijzer webshop.
Prototype/Forus/Webshop/Implementation/Westerkwartier | Webshop implementation of the westerkwartier webshop.

## Cloning a file
All files live in Figma. This means files don't have to be emailed around, and that there is no folder clutter on many different computers/clouds with many different versions. 

There simply is one "single source of truth". The master file is in Figma and can be accessed and edited (if you have the rights) trough one URL.

In figma, a file lives in an organisation project, or in your personal drafts. It is possible to clone a file from an organisation to your own drafts if the owner has enabled this.

<img width="406" alt="Screenshot 2020-01-28 at 11 09 39" src="https://user-images.githubusercontent.com/30194799/73254537-e46a8800-41be-11ea-89e1-c8855f136ea0.png">

### [Pull requests](https://www.figma.com/file/NsJsPJvWKqgoRtuTO6I8e5/Pull-Requests?node-id=3%3A112)
The pull requests file is a read only example file. If you have made an update or addition the library, you can propose for this update to be added to the platform using this format. 

* Copy this file to your drafts
* Add your proposed change(s) to the file
* Set the file to be public
* Comment on the pull requests file with a link to your file.







