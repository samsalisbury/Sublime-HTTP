HTTP Syntax for Sublime Editor

All 3 syntax files should be equivalent.





### Building the `.sublime-syntax` file from `.tmLanguage`

The included `httpspec.sublime-syntax` file is generated from `httpspec.tmLanguage` file using the conversion utility built into Sublime Text 3211.

In Subime Text with the `.tmLanguage` file open, use the command palette to run the "Plugin Development: Convert Syntax to .sublime-syntax" option. This should open a new file tab with the generated YAML that can be copied into the `httpspec.sublime-syntax` file here.

See <https://www.sublimetext.com/docs/syntax.html> for more general details on the `.sublime-syntax` file format
