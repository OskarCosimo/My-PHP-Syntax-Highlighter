## HOW TO INSTALL

Download the file .vsix and double click it; Visual Studio must be installed to install this extension.

## CHANGELOG

### Version 1.5.0
Fixed the option panel not showing up in Visual Studio 2026 (v18.x) due to a compatibility issue with the latest Visual Studio SDK. The panel is now fully functional and accessible under Tools -> Options -> PHP Syntax Highlighter -> Colors.
Fixed a minor bug where the syntax error detection would occasionally trigger false positives when editing large PHP files with complex nested structures. The detection logic has been refined to reduce false positives while maintaining accurate error reporting.

### Version 1.0.3
#### New Features
- Added keyword highlighting for PHP language constructs (echo, return, function, class, new, if, foreach, ...)
- Added built-in function highlighting covering the full PHP native function library (array_map, str_replace, json_encode, preg_match, session_start, ...)
- Added configurable colors page under Tools -> Options -> PHP Syntax Highlighter -> Colors

#### Improvements
- Extended Visual Studio compatibility to include Visual Studio 2026 (v18.x)
- Updated publisher website to oskarcosimo.com

### Version 1.0.2
- Improved highlighting matching for mixed braces
- Added marker in the scrollbar for matching braces

### Version 1.0.1
- Improved highlighting for braces and condition
- Improved speed and security

### Version 1.0.0
- Initial release
- Block highlighting for try-catch-finally
- Block highlighting for if-elseif-else-endif
- Block highlighting for foreach-endforeach
- Brace matching for curly, square, and round brackets
- Real-time syntax validation
- Support for inline and multiline keywords
