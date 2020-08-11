# espanso-package-cht

An espanso package for getting code snippets from [Igor Chubin's](https://github.com/chubin) console-oriented cheat sheet service [cht.sh](https://cht.sh). [Espanso](https://espanso.org/) is a free cross-platform text expander written in Rust.

![usage](./images/chtjs.gif)

For more information about espanso packages, read the [documentation](https://espanso.org/docs/).

## Usage

Available replacements:

| replacement      | description                 |
| ---------------- | --------------------------- |
| `:cht/{query}/`  | Code only, no comments.     |
| `:vcht/{query}/` | Verbose. Code and comments. |

Uses [passive replacement](https://espanso.org/docs/passive-mode/), so it is triggered by highlighting the text and double tapping your configured passive key.

## Installation

From [espanso hub](https://hub.espanso.org/packages/cht/):

```
espanso install cht
```

From source repo:

```
espanso install cht https://github.com/bradyjoslin/espanso-package-cht --external
```

## Dependencies

Passive replacement should be enabled in the espanso `default.yaml` configuration file:

```yaml
enable_passive: true
passive_key: CTRL
```

Requires `curl`.

## Package Details

Repository: [https://github.com/bradyjoslin/espanso-package-cht/](https://github.com/bradyjoslin/espanso-package-cht/)

