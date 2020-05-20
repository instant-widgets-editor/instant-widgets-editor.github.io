# Instant Widgets Editor

Is available at [https://instant-widgets-editor.github.io/](https://instant-widgets-editor.github.io/)

## Login

To login successfully you have to use your Github login and Personal Access Token (PAT)

### How to obtain Personal Access Token (PAT)?

It is easily done in few steps:

1. Login to your Github account at [https://github.com/](https://github.com/)
1. Follow this link [https://github.com/settings/tokens/new](https://github.com/settings/tokens/new)
1. Type your Github password:
![sreenshot](https://i.snipboard.io/qAWXUy.jpg)
1. Fill the Note input (something like *Personal Access Token for Instant Widgets Editor* would do)
![sreenshot](https://i.snipboard.io/h72dj9.jpg)
1. Make sure to mark following checkboxes:
![sreenshot](https://i.snipboard.io/fPlXFd.jpg)
1. Hit **Generate Token** button
![sreenshot](https://i.snipboard.io/3Hyaxo.jpg)
1. Make sure to copy and *save* your new personal access token now. You won’t be able to see it again!
![sreenshot](https://i.snipboard.io/W1kLKV.jpg)
1. Use your PAT each time you need to login to Instant Widgets Editor
![sreenshot](https://i.snipboard.io/1l0Y5h.jpg)

## Choose repository (country)

Once logged in there is a list of repositories to work with will be shown:
![screenshot](https://i.snipboard.io/QfugtV.jpg)

**Note:** Instant Widgets Editor displays repositories that are *available* to you. In case of empty page or some repos being missing, please request access to the repositories for your Github account.

## Edit Widgets

After choosing a repository you will be redirected to Widgets editing screen.

**Hint:** You can easily navigate in Instant Widgets Editor by changing *page* value in the URL to *login*, *repos* or *widgets*:
![screenshot](https://i.snipboard.io/GtBHeF.jpg)

Each environment (JIT, UAT and PROD) have their Widgets that can be added, removed, transfered and duplicated easily.

### Reordering Widgets

To change Widgets' order at an environment:
1. Press **Change Order** button next to the environment name
1. Drag the Widget to new position
1. Press **Change Order** button once again

### Editing Widgets

To edit a Widget:
1. Hover on Widget
1. Press **Edit** button that appears at the top right corner of the Widget
1. The editing popup will appear

### Copying Widgets

To copy a Widget:
1. Hover on Widget
1. Press **Copy** button that appears at the top left corner of the Widget
1. The copying popup will appear

## Publishing Changes

After any changes applied the corresponding environment will display two additional buttons: **Publish** and **Revert All Changes**.
Pressing **Revert All Changes** button discards all changes made for this environment.
Pressing **Publish** button will initiate Widgets' publishing process for given environment. Notifications about the procedure could be observed in the bottom left corner of the screen. After successfull reports in the notifications it is save to reload the page.
