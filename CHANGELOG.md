# CHANGELOG
## Version 0.2.2
* If the document gets closed, problems disappear.
* Removed all comments that had no real function.

## Version 0.2.1
* Changed the flag for `<a>`. It had way too many wavy lines!
* Remove typo from changelog

## Version 0.2.0
* Added Regex for `<input>`
* Refactored case handling
* Moved pattern case handling to `Patterns.ts`

## Version 0.1.3
* Fixed issue with filter tag being flagged on multiple patterns
* Fixed issue with multi-flag within `<head>` element
* Fixed issue with `<a>` not being flagged correct

## Version 0.1.2
* Removed foreach loop
* Moved `_diagnostics` from while loop
* Better Regex patterns
* Added Regex for `<title>`, multi-line `<head>`, multi-line `<a>`

## Version 0.1.1
* Moved RegEx patterns to Patterns.ts
* Refactored RegEx to be more readable
* Changed switch statements to be more forgiving with typos

## Version 0.1.0
* Added RegEx search qeuries for `<div>, <span>, <a>, <img>, <meta>, <html>`
* Added messages for above coding errors

## Version 0.0.2
* Changed extension type to `language-server`

## Version 0.0.1
* Auto-generated extension for Visual Studio Code with [Yocode](https://code.visualstudio.com/docs/extensions/yocode)