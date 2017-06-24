# UninstallChromeViaPowershell
This is a standalone setup.exe file from Chrome that can be used to run a powershell command to uninstall the program. Used for fixing unusual installation bug.

It is possible for the Chrome installer to get 'stuck' and believe you already have the browser installed. This will report the following error and prevent you from installing the browser: "This computer already has a more recent version of Google Chrome. If the software is not working, please uninstall Google Chrome and try again."

In some cases you may have already deleted all files related to Chrome. This repository contains setup.exe from the \Chrome\Application\[versionNumber]\Installer\ folder which is needed to execute the Powershell command needed to fix this bug.

This setup.exe file is not modified in anyway from the file distributed by Google. It is digitally signed by Google for verification.
