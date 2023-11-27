# application-ctac-sapo

<img src="assets/img_presenter_0.png" width="200px" height="200px" alt="Logo: person presenting at a confgerence"/>

CTAC SAPO XWiki application for conferences and papers

Based on the XWiki "Events" application: https://github.com/xwiki-contrib/application-events

Supports
  - Conferences with URL, dates, location abstract and proceedings deadlines
  - Presentations associated with conferences, with author(s), reviewer(s), status, type, abstract, slides, proceedings, approvals
  - Notification of new presentation by email (requires [XWiki Script Component extension](https://extensions.xwiki.org/xwiki/bin/view/Extension/Script%20Component/) be installed on the root namespace)
  - Summary reports giving number of presentations per year, per reviewer, and many more
  - Also includes SAPO navigation panel based on XWiki "Applications" panel

## Installation

From the [releases page](https://github.com/sfegan/application-ctac-sapo/releases), download the XAR file for the version you wish to install (note XAR is a standard Zip file whose contents describe the application to the XWiki system). On your XWiki instance, go to the "Administer wiki" page by first cliking on the button on the top-right of the Wiki page that has three horizontal lines. Then navigate to "Content" and then "Import". Upload the XAR file to the system in the "Upload a new package" section of the page, and then click on the uploaded version in the "Available packages" section. This will present a tree that allows you to select the directories and/or files you wish to install. You can select a subset, or install them all as you wish.

## Development

Development of the application should be done in the XWiki system itself by editing the classes, scripts, sheets etc using the edit buttons. Seek out help on the XWiki webpages for help on this. When you have modified the system to suit your needs, you should download the changes to your computer and merge them into the github version of the application.
