# Change Log

All notable changes to the "language-omsi" extension will be documented in this file.

## [1.1.1] - 2021-11-14
Code cleanup and fixes by [Road-hog123](https://github.com/Road-hog123):
- Use consistent indentation, whitespace and newlines
- Fix omsiscript scopes
- Fix omsiscript numeric constants
- Add `$d` operator
- Reuse regexes to remove duplication

## [1.1.0] - 2021-09-13
Fixes and improvements by [sjain](https://github.com/sjain882) and [Road-hog123](https://github.com/Road-hog123):
- Fix highlighting for `IntToStrEnh` keyword
- Add code folding support for OSC files

## [1.0.0] - 2021-05-25

Various fixes from [Road-hog123](https://github.com/Road-hog123):
- Fix comments and operators not being included (scripting language)
- Categorize numbers under `omsi.script`, rather than `omsi.cfg` (scripting language)
- Add `frame_ai` as a predefined macro name
- Allow `+` and `-` in variable, macro and trigger names
- Add stack positions 8 and 9 (they seem to work even if undocumented)

## [0.2.0] - 2020-02-27

- Remove auto-closing single quotes for scripting language
- Fix parameters for money point tags

## [0.1.0] - 2020-02-21

- Initial release