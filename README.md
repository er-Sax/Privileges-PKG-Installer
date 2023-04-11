# Privileges-PKG-Installer

This repository contains pkg installer of SAP Privileges application. </br>
This pkg file is ready to deploy via Jamf or other MDMs (except Intune, thanks M$...). </br>
Installer contains Privileges.app and postinstall script to install application helper. It allows to install app on MacBooks with standard-only account (by default admin rights are required to helper installation, without helper you can't request temp admin, you want to request admin because you are not an admin ¯\_(ツ)_/¯). </br>

<h3>Special thanks</h3>
Privileges app: https://github.com/SAP/macOS-enterprise-privileges </br>
Postinstallation script: https://github.com/autopkg/rtrouton-recipes/blob/master/Privileges/Scripts/postinstall </br>
