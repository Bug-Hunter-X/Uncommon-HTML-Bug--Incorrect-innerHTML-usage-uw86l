# Uncommon HTML Bug: Incorrect innerHTML usage
This repository demonstrates an uncommon bug related to the usage of `innerHTML` in HTML. The bug arises from attempting to set the `innerHTML` property to a non-string value, leading to unexpected behavior or errors.

## Bug Description
The bug occurs when attempting to set the `innerHTML` property of an HTML element to a non-string value, such as a number.  This results in the value being implicitly converted to a string, but can lead to unexpected formatting or rendering issues in complex scenarios. This can lead to difficulties in debugging as it doesn't throw an immediate error.

## Bug Solution
The solution is to always ensure that the value assigned to the `innerHTML` property is a string.  Explicitly convert any non-string values to strings before assigning them to `innerHTML`. 