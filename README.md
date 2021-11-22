# UFOs

## Overview of Project

The purpose of this project is to visualize the ufo sighting data, and build a dynamic filter based on user input.

## Result

To use the dynamic filter in the dashboard, you need to enter the filter to the left side box.

The filter key value pair are updated when there is a input to the corresponding input box. When the dictionary holding filter key value pairs changes, the data are automaticly filtered and displayed.

## Summary

One of the drawback of this webpage is that there is inpute validation to the filter data. Although there is a placeholder text in the box, there are still problem arise from not having validation. Maybe people enter unexpected value and no return from the table.

For example the datetime filter could use DD/MM/YYYY as place holder instead of 1/10/2010, so it is easier to tell which part is the month and which is day. It would be better to use a dropdown selection for shape of ufo sighting instead of text input, because it is hard for user to know what are the possible shape description.
