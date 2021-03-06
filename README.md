# About MTML Completions 

MTML Completion is an add-on program package for Sublime Text 2. This complements Movable Type Template Tags when you use Sublime Text 2.  
This package includes some tags of [DynamicMTML](https://github.com/movabletype/DynamicMTML)  plugin.

## Installation

### With Package Control

* Bring up the Command Palette (Command+Shift+p on OS X, Control+Shift+p on Linux/Windows).
* Select "Package Control: Install Package" .
* Select "MTML Completions" when the list appears.

### With Git

Please clone into your Sublime Text 2 package directory.

```
cd /path/to/your/Sublime Text 2/Packages
git clone https://github.com/bit-part/MTML-ST2
```

## Preference

You can change the format of Template Tags.

### mtml_prefix

	no setting => <mt:EntryTitle />
	"mtml_prefix": "MT:" => <MT:EntryTitle />
	"mtml_prefix": "MT"  => <MTEntryTitle />

### mtml_function_tag_type

	no setting => <mt:EntryTitle />
	"mtml_function_tag_type": "dollar" => <$mt:EntryTitle$>
	"mtml_function_tag_type": "none" => <mt:EntryTitle>

## Usage

You can use this feature when you input "<" in html or php file. When you set extension as ".mtml" or ".tmpl" , please change Syntax as html.

For modifier, you run "Edit > Show Completions [cntrol + space]" when you input a space and a few calactors.

## Example

![Example](http://bit-part.github.com/data/img_mtml-st2.png)

* [B] : Block Tag
* [F] : Function Tag
* [C] : Conditional Tag

![Modifier Example](http://bit-part.github.com/data/img_mtml-st2_modifier.png)

Ctrl + Space

* [M] : Modifier

---

_Movable Type is a registered trademark of Six Apart, the Ltd._
