# SchTask-Installer
Python CLI for creating Scheduled Task Installer files for Python projects

# Requirements
- The CLI can be downloaded from PIP
- It can be run from anywhere on the system
- Upon running, it asks a few questions, on how the Scheduled Task should be set up
  - When should the task run (on startup, every x hours, etc)
  - Run whether the user is loggeed on
  - Which file to run
  - Should it call additional files during the install project
- The end result is an `install.bat` file, which upon running creates a Scheduled Task

# Resources
[CLI in PIP](https://stackoverflow.com/questions/56534678/how-to-create-a-cli-in-python-that-can-be-installed-with-pip)
