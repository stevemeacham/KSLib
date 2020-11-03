# KSLib Library Summary

This repository is created from libraries submitted by multiple kOS users. All contributions are accepted as long as they satisfy the set requirements. As such there may be multiple libraries that provide the same functionality but take different approaches to it.

This is an attempt at summarizing and categorizing the libraries by their use cases.

## Control

* [lib_pid.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_pid.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_pid.md) : provides functions for creating a PID controller. This functionality has been superseded by kOS built-in `PIDLoop()`.
* [lib_raw_user_input.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_raw_user_input.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_raw_user_input.md) : Listens for action groups in a list and returns the index of the activated action group.

## Data Structures

* [lib_enum.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_enum.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_enum.md) : provides functions to manipulate structures like lists, stacks, queues etc.

## External Mod Compatibility

* [lib_realchute.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_realchute.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_realchute.md) : Provides a way to (dis)arm, deploy and cut chutes if the RealChute mod is installed.

## File I/O

* [lib_file_exists.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_file_exists.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_file_exists.md) : checks whether a given file exists or not on the current volume. This functionality has been superseded by kOS built-in `VOLUME:EXISTS()`.

## Maths and Statistics

* [lib_running_average_filter.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_running_average_filter.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_running_average_filter.md) : gives a running average of a given list of numbers.

## Navigation

* [lib_circle_nav.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_circle_nav.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_circle_nav.md) : provides functions to help with great circle / geodesic navigation while in the atmosphere or on the surface. For example, finding out the compass heading of a waypoint to fly there along the shortest path.
* [lib_location_constants.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_location_constants.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_location_constants.md) : provides latitude longitude values for various locations on some bodies.
* [lib_navball.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_navball.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_navball.md) : provides various navball state values (heading, pitch, roll, etc) of several kOS structures that can be considered to have such state.
* [lib_navigation.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_navigation.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_navigation.md) : provides a range of functions to used in calculations of both space, atmospheric and surface navigation.

## Programming Utilities

* [lib_exec.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_exec.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_exec.md) : allows executing commands and evaluating expressions from strings.

## Space Navigation

* [lib_lazcalc.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_lazcalc.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_lazcalc.md) : does launch azimuth calculation.

## Terminal Utilities

* [lib_gui_box.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_gui_box.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_gui_box.md) : draws ASCII boxes in the terminal.
* [lib_input_string.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_input_string.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_input_string.md) : creates an on-screen keyboard inside the terminal.
* [lib_input_terminal](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_input_terminal.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_input_terminal.md) : for string input by typing in the terminal.
* [lib_list_dialog.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_list_dialog.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_list_dialog.md) : helps with long list navigation.
* [lib_menu.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_menu.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_menu.md) : draws an interactive menu in the terminal.
* [lib_num_to_formatted_str.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_num_to_formatted_str.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_num_to_formatted_str.md) : provides functions to format numbers and date-time values in standard formats. For example, numbers with given digit precision and SI unit, time broken into years, months, days etc.
* [lib_num_to_str.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_num_to_str.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_num_to_str.md) : formats numbers to specified number of digits.
* [lib_number_dialog.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_number_dialog.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_number_dialog.md) : draws a dialog box for numerical input in the terminal.
* [lib_seven_seg.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_seven_seg.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_seven_seg.md) : creates a seven segment display to show single digit numbers.
* [lib_str_to_num.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_str_to_num.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_str_to_num.md) : converts numerical strings into numbers. This has been superseded by kOS built-in `STRING:TONUMBER()`.
* [lib_term.ks](https://github.com/KSP-KOS/KSLib/blob/master/library/lib_term.ks) / [docs](https://github.com/KSP-KOS/KSLib/blob/master/doc/lib_term.md) : a primitive terminal ASCII graphics library. Helps with drawing straight lines, circles and elliptical arcs.

---
Copyright © 2019,2020 KSLib team

This work and any code samples presented herein are licensed under the [MIT license](../LICENSE).
