# Time reporter [Build](https://github.com/ceusse/time-reporter/actions/workflows/build.yml/badge.svg)
Tool to automatically report time in Jira and Dynamics 365 daily

## Motivation
I'm a pretty lazy dude when it comes to manual work.
I rather spend 40 hours in a software that takes away that from me for the rest of my life than filling a report for half an hour.
If you are like me, you are welcome to install, or even better, contribute.
This is also an excuse to learn Electron, and the GitHub tool set.

## How it works
The reporter will connect to Jira to download the tasks assigned to you.
You can plan for the day on which tasks are you going to work on and start a timer that will give you the summary of the work done and will post it to Jira or Dynamics for you.

## Usage
Simply install , connect to the platforms and send the report whenever you like.
Service will keep tracking time if you close the main window.
You can open it again suing the icon in the system tray.

## Features
- Integration with JIRA
- Integration with Dynamics 365
- Track idle time

## Coming soon
- Reminder to post the report 
- Reminder to do a pause
- Configure how long will the pause be
- Implement the option to work with Pomodoro 
- Enable default options to send report
- Autodetect when a task changes status and report time accordingly.
- Completely automated work: If conditions are met and configuration is done, the reporter will post the time without telling you.
- Notifications when a report cannot be uploaded
- Reported time monitoring: Check if you are missing time each week and maybe fill it for you?
