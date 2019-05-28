# vscode-language-ttcn
## TTCN-3 Language Support for Visual Studio Code
## Change Log

#### 0.12.0
- Added support for tokenizing escaped double quotes
- Fixed issue with user-defined keyword matching

#### 0.11.0
- Added snippets for TTCN-3
- Added support for altsteps with interleave functionality <sup>TTCN-3:2019</sup>
- Added support for control functions <sup>TTCN-3:2019</sup>
- Added support for keywords from object-oriented features <sup>TTCN-3:2019</sup>
- Added support for keywords and operators from advanced matching features <sup>TTCN-3:2019</sup>
- Added support for qualified form of enum values <sup>TTCN-3:2019</sup>
- Added support for tokenizing alt (array notation) operator
- Fixed tokenization of identifiers preceded by control and deterministic modifiers
- Fixed tokenization of user-defined keywords
- Fixed tokenization of modules, functions, and variables using dot notation
- Fixed tokenization of illegal identifiers

#### 0.10.0
- Improved support for highlighting user-defined keywords
- Fixed issue with matching comma-separated identifiers
- Fixed issue with matching variables followed by operators

#### 0.9.0
- Improved support for highlighting user-defined keywords
- Improved support for highlighting function modifiers
- Fixed more issues with highlighting identifiers
- Fixed issue with matching inequality and rotate operators

#### 0.8.0
- Fixed issue with highlighting identifiers paired with built-in keywords
- Fixed missing highlight when defining user-defined types

#### 0.7.0
- Added support for pre-processed TTCN files (.ttcnpp) \[[@oakimk](https://github.com/oakimk) in [#17](https://github.com/ealap/vscode-language-ttcn/pull/17)\]
- Fixed issue with invalid identifiers with multiple special characters
- Fixed issue regarding user-defined types with assigned values
- Modified for a more consistent and optimal usage of regular expressions

#### 0.6.0
- Added a separate rule for invalid identifiers for const/template/var
- Added support for highlighting colon (:) (undocumented in TTCN-3)

#### 0.5.0
- Added highlighting for invalid identifers
- Added highlighting for invalid numeric strings
- Added highlighting for invalid symbols
- Added highlighting for range symbol
- Modified pattern for matching statement separators
- Modified pattern for matching string operator (&)
- Replaced impossible match under invalid patterns
- Removed end-of-line match when highlighting identifiers
- Modified regular expression to only match hexadecimal digits A-F or a-f
- Fixed incorrect name key for bitstring and octetstring

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