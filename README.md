# OMSI Syntax highlighting and Snippets for Visual Studio Code

Provides basic syntax highlighting and snippets to:
+ OMSI configuration files (`.cfg`,`.bus`,`.ovh`, `.cti`,`.sco`,`.hum`)
+ OMSI scripts (`.osc`)

## Features

The syntax highlighting for configuration files is very basic and only includes the tags (e.g. `[mesh]`), whilst for the scripting language it is much richer.

The snippets for the configuration files are provided for almost all the known tags and consist in the tag with a list of parameters that can be completed. The goal is to speed up common tasks.

![CTI snippet demonstration](./images/screencast-cti.gif)

The snippets for the scripts are provided for macro and trigger definitions
and for all the operations like `L.L. L.$. ...`, for which the snippet can
be recalled with its non-dotted counterpart (i.e. `ll ls ...`).

![Script snippet demonstration](./images/screencast-script.gif)

## Extension Settings

No additional settings are provided.

## Known Issues

It's lonely in here.

## Release notes

### 0.1.0
Initial release
