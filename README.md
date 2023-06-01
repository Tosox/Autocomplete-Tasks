# Autocomplete Tasks

> Note: If you have any suggestions write me a [DM](https://www.moddb.com/messages/compose?to=Tosox) on Moddb or Discord [Tosox#0573]

## Description

This addon completes tasks as soon as the conditions are met without having to return to the task giver. By default it completes all bounty, mutant killing and assault tasks.

## What is new?

Since [AeneasH's](https://www.moddb.com/members/aeneash) [Autocomplete Unofficial](https://www.moddb.com/mods/stalker-anomaly/addons/autocomplete-unofficial-1-5-1) following things have changed:
* Compatibility with custom tasks (e.g. [Weird Task Framework](https://www.moddb.com/mods/stalker-anomaly/addons/weird-tasks-framework) tasks)
* More compatibility because of DLTX
* Improved performance
* MCM support

## Installation

* Make sure that the [Modded Exes](https://github.com/themrdemonized/STALKER-Anomaly-modded-exes) are installed
* Download the [latest release](https://www.moddb.com/mods/stalker-anomaly/addons/dltx-unofficial-autocomplete-v4)
* Install the mod (preferably with [Mod Organizer](https://github.com/ModOrganizer2/modorganizer/releases/))
* Open the game and enjoy

## I want to enable auto-completion for task X
1. Get the ID of the task. It should look something like this: bar_visitors_barman_stalker_trader_task_2. You can find all vanilla tasks defined in this directory after unpacking the game files: gamedata/configs/misc/task/tm_\*.ltx. If you only know the name of the task you can check gamedata/configs/text/[eng/rus]/st_quests_\*.xml and search for the name of the tasks. Next, copy the text above the title in the quotation marks without "_name" from the end. Now you have the task id.
2. Open the following file from the Autocomplete Tasks addon: gamedata/configs/misc/task/mod_task_manager_autocomplete_tasks.ltx. Here you already have some examples how the result should look like. Go to a new line and just follow the pattern and define your task: ![your_task_id]autocomplete = true
