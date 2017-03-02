# Craft Collections Sketch Plugin

This plugin automates the creation of "collection" symbols to make importing all variants of a symbol from a Craft library.


## Using the Plugin

For example, you have several symbols that all represent various button states (hover, disabled, etc.) Rename these symbols so that they're "grouped": `Buttons/Normal`, `Buttons/Hover` or `Buttons/Disabled`, etc.

_This will also help you logically group them in the Insert Symbol menus._

Then create an empty symbol and name it `Collections/Buttons`.

You can then use the shortcut **^⇧⌘G** (Command + Control + Shift + G) to run the plugin.

Then enter the prefix of the symbols you want to create an instance group ("collection") of -- in the above example you'd enter "Buttons" (case sensitive to your naming convention).

This will create instances of all master symbols prefixed with `Buttons/*` and put these instances into the `Collections/Buttons` symbol. You can then import the collections symbol into your Craft library and users can import it to have access to all variants of `Button`.


## Installing the Plugin

Simply clone this repository to your `~/Library/Application Support/com.bohemiancoding.sketch3/Plugins/` folder, restart Sketch, and access it from the Plugins menu or using the keyboard shortcut above.


## Use a different naming convention?

Feel free to fork this plugin and change the text matching bits (or any other part of it for that matter).