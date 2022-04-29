# Change Log

All notable changes to the "language-omsi" extension will be documented in this file.

## [1.3.0] - 2022-04-30
New snippets and syntax highlighting by [jem-suu](https://github.com/jem-suu):

- Add snippets and seperate syntax highlighting for System variables
- Add new cfg snippets: `[usescripttexture]`, `[smoke]` and `[texchanges]`
- Fix `[matl_allcolor]

## [1.2.0] - 2021-12-24
New snippets and fixes by [zheka20012](https://github.com/zheka20012):

Fixed:
- `[mesh]` snippet now doesn't have index after name
- `[newanim]`, `[texttexture_enh]` - fixed choose snippets

Added:
- comment selected text
- `[alphascale]`
- `[matl_bumpmap]`
- `[matl_envmap_mask]`
- `[matl_transmap]`
- `[matl_freetex]`
- `[matl_texaddress_*]`
- `[matl_texcoordtransX/Y]`

Bumped VSCode requirement to 1.60+.

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