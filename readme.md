## 1-Click Child-Links ##

<a href="https://marketplace.visualstudio.com/items?itemName=ruifig.vsts-work-item-one-click-child-links" target="_blank">1-Click Child-Links</a>

Add Child-Links from predefined templates with a single click.

Team Services allows you to create work item templates.
With work item templates you can quickly create work items which have pre-populated values for your team's commonly used fields.

1-Click Child-Links uses predefined templates and add them as a Child Link.

It follows process work item types and workflow

* <a href="https://www.visualstudio.com/en-us/docs/work/guidance/agile-process-workflow" target="_blank">Agile</a>
* <a href="https://www.visualstudio.com/en-us/docs/work/guidance/scrum-process-workflow" target="_blank">Scrum</a>
* <a href="https://www.visualstudio.com/en-us/docs/work/guidance/cmmi-process-workflow" target="_blank">CMMI</a>

### Setup your templates ###

<a href="https://www.visualstudio.com/en-us/docs/work/productivity/work-item-template#manage" target="_blank">Manage work item templates</a>

<img src="src/img/screen01.png" alt="Create your task templates" />

### Create / open a Work Item ###

Find 1-Click Child-Links on toolbar menu

<img src="src/img/screen02.png" alt="1-Click Child-Links on the menu"/>

### Done ###

Now you have Childs associated with the Work Item

<img src="src/img/screen03.png" alt="Done"/>


## Usage ##

1. Clone the repository
1. `npm install` to install required local dependencies
2. `npm install -g grunt` to install a global copy of grunt (unless it's already installed)
2. `grunt` to build and package the application

### Grunt ###

Basic `grunt` tasks are defined:

* `package-dev` - Builds the development version of the vsix package
* `package-release` - Builds the release version of the vsix package
* `publish-dev` - Publishes the development version of the extension to the marketplace using `tfx-cli`
* `publish-release` - Publishes the release version of the extension to the marketplace using `tfx-cli`

Note: To avoid `tfx` prompting for your token when publishing, login in beforehand using `tfx login` and the service uri of ` https://marketplace.visualstudio.com`.

## Credits ##

Clone from https://github.com/cschleiden/vsts-extension-ts-seed-simple
