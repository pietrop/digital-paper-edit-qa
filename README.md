# Digital Paper Edit - QA

QA docs for[ Digital Paper Edit Project](https://github.com/pietrop/digital-paper-edit-client), [syncs with Github repo](https://github.com/pietrop/digital-paper-edit-qa).

This doc provides a lightweight set of steps and checklists for manual QA test. This should be done before every major release.

_The assumption underlying this doc is that anyone, even without technical skills, should be able to conduct QA testing._

## Overview

Digital Paper Edit it's a project to make working with audio and video interviews easier and faster. Please see project repository the Github [README](https://github.com/pietrop/react-transcript-editor/blob/master/README.md) page, for an overview of its architecture and how it works.

## Where to test

The app can be tested by downloading a release from the release section of the electron repository [https://github.com/pietrop/digital-paper-edit-electron/releases](https://github.com/pietrop/digital-paper-edit-electron/releases)  

Alternatively for deploying the app to the latest version see the deployment instructions in the [digital paper edit electron README](https://github.com/pietrop/digital-paper-edit-electron#deployment).

## Where to log bugs:

If you find any bugs or issues, please [open an issue in Github](https://github.com/pietrop/react-transcript-editor/issues/new?template=bug_report.md) label it as 'QA Testing' and assign it to [@pietrop](https://github.com/pietrop).

If it's connect to one or more of the QA steps listed below make a note of the corresponding number.

For things like typos feel free to directly do a PR with the changes.

## Browsers/devices:

By default we aim for the app work on the following operating systems:

*  Desktop - Mac 

Other operating system and devices are not part of out core effort but we welcome feedback to maintaining a working version for the following operating systems:

*  Desktop - Windows 
*  Desktop - Linux

When you raise an issue please indicate at a minimum the 

* Operating system \(eg Mac\)
* Operating system version number \(eg OSX 10.14.6\)
* Digital Paper Edit version \(eg `1.0.3-alpha.9`\)
* The number of the QA point being tested that it's failing, if applicable 

  


