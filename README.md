# vscode-language-ttcn

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version/ealap.language-ttcn.svg)](https://marketplace.visualstudio.com/items?itemName=ealap.language-ttcn)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/ealap.language-ttcn.svg)](https://marketplace.visualstudio.com/items?itemName=ealap.language-ttcnx)

## TTCN-3 Language Support for Visual Studio Code

Provides TTCN-3 language support for Visual Studio Code

### Features
- Syntax highlighting<br /><p><img src="https://raw.githubusercontent.com/ealap/vscode-language-ttcn/dev-ealap/images/vscode-ss-ttcn3.png" alt="Figure 001. TTCN-3 Sample Code" /></p><sup><i>Theme: <a href="https://marketplace.visualstudio.com/items?itemName=teabyii.ayu">Ayu Dark by teabyii</a></i></sup>

### Release Notes
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

#### Older releases
See [CHANGELOG](https://raw.githubusercontent.com/ealap/vscode-language-ttcn/master/CHANGELOG.md)

### Reference
[TTCN-3 Core Language Specification v4.10.1 ](http://www.etsi.org/deliver/etsi_es/201800_201899/20187301/04.10.01_60/es_20187301v041001p.pdf)