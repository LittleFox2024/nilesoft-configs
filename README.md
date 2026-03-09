# Configs for Nilesoft Shell

This repo will contain config(s) for Nilesoft Shell. Mainly created to hold taskbar modification items recreated from Windows 10.

## Restoring Windows 10 taskbar modification items

Windows 10 had more options in the taskbar's context menu allowing for some settings to be shown or hidden that Windows 11 removed. Nilesoft shell does not come preconfigured with any options to restore these. However, they are not too hard to get back. All of the options are registry keys, and even better, Explorer watches these for changes meaning a shell restart is not required. The main registry keys are these:

* Search: `HKCU\Software\Microsoft\Windows\CurrentVersion\Search\SearchboxTaskbarMode`
* Task View: `HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced\ShowTaskViewButton`
* Widgets:
* Virtual Touchpad:
* Virtual Keyboard:
* Centered Taskbar:
