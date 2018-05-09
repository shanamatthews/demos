# Top tips & tricks for live demos

How to look like a coding rockstar on stage with Azure and VSCode.

[comment]: # (Consider adding screenshots for each of these tips)

## Tip 1: Customize your [Azure Portal](https://portal.azure.com/)

[comment]: # (If you're doing an Azure demo - you're probably going to have the Portal up)

* Disable your toasts
* Change your theme
  * DOUBLE CLICK TO CHANGE THEME -> Wrong theme? Don’t panic. Double click.
  * High contrast options available
* Customize your dashboard

    [comment]: # (You know you can pin your resources to the dashboard, but…)

  * Pin new & cool things to the dashboard (quickstart, clock)
  * Resize them, rearrange them – just like win10 start menu

* Subscription filter

    [comment]: # (you have multiple subscriptions, don’t want everyone to see your personal resources. Those are the ones I’m making Satya pay for.)

## Tip 2: Cloud shell is your friend

  [comment]: # (if you ever have to demo on a machine that isn't yours, or you can't install command line tools on cloud shell will save your butt.)

* Azure CLI 2.0 is installed
* Use bash or PowerShell.
* Change the text size
* Open in a new window
* Drag & drop files – easy to upload into your VM or other Azure resource
* Check VM status – MOST foolproof way to do it
* FYI - cloud shell also exists in docs - [try it button](https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart)

## Tip 3: Show your users how to save $

  [comment]: # (this is for you and your audience. If you're starting a VM to use for a demo - are you going to remember to shut it back down?)

* VM Autoshutdown feature
* Delete resource groups
* Azure android/iOS apps

    [comment]: # (if you realize at midnight, in bed, that you forgot to shut down your VM - as I have... a few times. You don't have to get out of bed!! Download the Portal app on your phone and shut that sucker down.)

    [comment]: # (guess what? the app also has CLOUD SHELL! so if you have to do something more complicated, it's as easy as texting... a computer... with perfect syntax ;)

## Tip 4: Make the code easy to read

* Zoom in properly! (ctrl + wheel or ctrl + =/-)
* Zen mode in VSCode
* Fonts and colors

## Tip 5: Use code snippets

* [VSCode extensions](https://code.visualstudio.com/docs/editor/userdefinedsnippets)
* File -> Preferences -> User Snippets
* Carefully choose your snippet size: large is fine for boilerplate, but use small, incremental snippets for anything your audience should follow along with

```python
print("hello MSPs!")
```

## Bonus tips

* Tips & tricks section and keyboard shortcuts section within VSCode!

### VSCode features

* VSCode log points
* VSCode interactive playground (Help > Interactive Playground.)

### Keyboard shortcuts

Command palatte (ctrl + shift + p)
keyboard shortcuts ?
alt + up/down moves a line of code up or down
ctrl + m/h
ctrl k, c for commenting/uncommenting
Intellisense can be invoked with Ctrl+Space
Formatting Shift + Alt + F