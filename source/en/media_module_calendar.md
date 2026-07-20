---
toc: "widgets"
maxHeadingLevel: 3
minHeadingLevel: 2
alias: "media_module_agenda"
excerpt: "Display Calendar events pulled in from an iCal feed"
keywords: "ical feed"
persona: "content manager, webhook triggers"
---

# Calendar

Display Calendar events pulled in from an iCal feed anywhere on a Layout using **Elements** or select a **Static Template** to display results in Layouts/Playlists.

Calendar data is provided by an iCal feed which will feed into configured Elements and Static Templates.

{tip}
Ensure that the ICS feed URL is available to the CMS. If the feed loads in a browser without authentication then the feed should display in the CMS without issue.

For further information on how to view your Google Calendar in applications, use the following link selecting the **Get your calendar (view only)** option: https://support.google.com/calendar/answer/37648?hl=en
{/tip}

## Overview

- Return events within a specified date range.
- Options to exclude all day and current events from the feed so they won't be shown.
- Use event and calendar timezones.
- Set duration per item.
- Specify how many events to display.
- Execute a Web Hook trigger when certain conditions are detected.
- Data for this media is cached by the Players for off-line playback.

### Web Hook Triggers 

Trigger a Web Hook [Action](layouts_interactive_actions.html) when there is a **Current Event** or **No Event** from the Trigger tab.

{tip}
**Example Scenario**:

A user has a meeting room calendar configured using the Calendar Widget on a Layout which shows the current occupancy for a room and would like to change LED lights to show when vacant or in use.

- The user would first need to create [Shell Commands](displays_command_functionality.html#content-shell-commands) which issued commands to an LED IoT device or the inbuilt LEDS's on some of the Philips Commercial Displays.
- Next an [Interactive Action](layouts_interactive_actions.html) would need to be defined on the **Layout**, which would **Navigate to Widget** and **Target the Screen**, with the [Shell Command Widget.](media_module_shellcommand.html) 
- From the **Trigger** tab, assign the code's to trigger the **Web Hooks** for **Current Event** and **No Event**.

{/tip}

