# LINKEDIN

![logo](https://assets.gitlab-static.net/uploads/-/system/project/avatar/16769270/LinkedIn-logo.jpg)

## INDEX

- [LINKEDIN](#linkedin)
  - [INDEX](#index)
  - [BADGES](#badges)
  - [FIRST UPDATE](#first-update)
  - [INTRODUCTION](#introduction)
  - [INSTALL](#install)
    - [EXTENSION INSTALLATION](#extension-installation)
    - [USE THE AUTOMATION SCRIPT](#use-the-automation-script)
    - [CLEAN UP UNANSWERED REQUESTS](#clean-up-unanswered-requests)
  - [LICENSE](#license)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/linkedin/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/linkedin/commits/master)

## FIRST UPDATE

Date: 01-01-01

## INTRODUCTION

This repository contains a script for automated Linkedin

## INSTALL

### EXTENSION INSTALLATION

To use this script, we will need to install an extension, go to the Google Chrome web store and install [TamperMonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).

Once the extension is installed in your browser, go to [greasyfork.org](greasyfork.org/…/26829-add-all-linkedin-users-for-2017-version) and click on the green Install this script button.

### USE THE AUTOMATION SCRIPT

To use the script you just installed, just go to LinkedIn on the Network page: www.linkedin.com/mynetwork/?BotMe=true. The "BotMe = true" parameter added to the URL is required if you want to enable automation.

Once on this page, you will see your page load from top to bottom on its own (auto-scroll) for approximately 2 minutes (30 loads). Then a new page will open on its own, and the contacts loaded on the previous one will be automatically added.

### CLEAN UP UNANSWERED REQUESTS

Load your page beforehand (www.linkedin.com/mynetwork/invitation-manager/sent) by going down to the bottom of the page to load all pending requests.

Then open the developer console of your browser (Google Chrome) by pressing the F12 key on your keyboard. Then copy / paste this little command:

```$('button.mn-person-card__person-btn-ext.button-tertiary-medium-muted').click();```

>This will have the effect of clicking on all pending invitation buttons, and will cancel these requests automatically.

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/linkedin/blob/master/LICENSE)
