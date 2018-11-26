# vscode-language-ttcn
## TTCN-3 Language Support for Visual Studio Code
## Change Log
#### 0.4.0
- Added highlight for comma-separated identifiers used when defining multiple friend modules
- Added highlight for arrays and their indices when followed by the assignment operator
- Fixed highlight for '-infinity' & 'infinity' keywords used as lower or upper value limit in ranges.
- Fixed highlight for 'repeat' keyword not matching because pattern used was misspelled as 'repeate'
- Fixed highlight for user-defined types defined inside sets, records and templates
- Fixed highlight for user-defined objects and their fields
- Fixed highlight for keywords usually followed by "(", these will now be highlighted the same as function identifiers
- Fixed highlight for keywords not usually followed by "(", these will now be highlighted the same as reserved words
- Modified the definition and arrangement of rules for clarity
- Modified the comments for rules matching symbols
- Removed multiple rules matching a single keyword

#### 0.3.0
- Fixed issue with highlighting user-defined types
- Fixed issue with highlighting numeric strings

#### 0.2.0
- Fixed issue with identifiers not colorized when curly brace is typed on the next line
- Fixed issue with user-defined types mix matching to other rules
- Added extension icon

#### 0.1.0
- Initial release