# Changelog

## v1.0.0:
* Initial release

## v1.1.0:
* Renamed the project "Unofficial Autocomplete v4" to "Autocomplete Tasks"
* Added a "PDA Check" MCM option
* Edited language strings
* Optimized code

## v2.0.0:
* No longer requires Modded Exes (for now)
* Added MCM options for different task categories
* Added a "Compensate Item Rewards" MCM option
* Added Milspec PDA to "PDA Check"
* Edited language strings

## v2.0.1:
* Fixed index a nil value

## v2.0.2:
* Fixed release v2.0.1

## v2.0.3:
* Changed the default value of the coefficient of "Compensate item rewards"
* Fixed compensation for multi use items with a defined amount
* Optimized code

## v2.0.4:
* Fixed item compensation not working for special cases

## v2.1.0:
* Receive a message from the task giver after completing the task
* All money rewards after item compensation come in one single money reward
* Lowered default item compensation coefficient
* Customizable autocomplete check interval and more in the MCM settings
* Fixed a CTD when compensating item rewards

## v2.1.1:
* Fixed a CTD when sending the task finish message
* Fixed rare 0 money rewards
* Fixed deletion of on_complete instructions with no arguments
* Added task "esc_2_12_stalker_wolf_task_3" to the blacklist by default

# v2.1.2:
* Added MCM option descriptions
* Reworked Russian translation
* Slightly adjusted item compensation formula
* Removed the reward and task giver message delay for now since it was causing issues
* Fixed task giver message for certain NPCs

# v2.1.3:
* Added support for Hostage Tasks
* Added support for Spy Extraction Tasks
