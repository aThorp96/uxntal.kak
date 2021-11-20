# Kakoune UXNTal Syntax Highlighting

Syntax highlighter for [uxntal](https://wiki.xxiivv.com/site/uxntal.html) code in [Kakoune](kakoune.org). Sourcing this `.kak` file in your `kakrc` should enable syntax highlighting on any `.tal` file you open.

## Usage
Until I figure out how to use this with [plug.kak](https://github.com/andreyorst/plug.kak) you'll have to do things the hard way:

- Clone this repo into `$kakrc_directory/plugins`
- Include the following line in your Kakrc:
```
source "%val{config}/plugins/uxn.kak/rc/filetype/tal.kak"
```
- Open any `.tal` file
- Enjoy!
