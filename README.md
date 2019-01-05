# vscode-language-ttcn

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version/ealap.language-ttcn.svg)](https://marketplace.visualstudio.com/items?itemName=ealap.language-ttcn)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/ealap.language-ttcn.svg)](https://marketplace.visualstudio.com/items?itemName=ealap.language-ttcnx)

## TTCN-3 Language Support for Visual Studio Code

Provides TTCN-3 language support for Visual Studio Code

### Features
- Syntax highlighting<br /><p><img src="https://raw.githubusercontent.com/ealap/vscode-language-ttcn/dev-ealap/images/vscode-ss-ttcn3.png" alt="Figure 001. TTCN-3 Sample Code" /></p><sup><i>Theme: <a href="https://marketplace.visualstudio.com/items?itemName=teabyii.ayu">Ayu Dark by teabyii</a></i></sup>

### Release Notes
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

#### Older releases
See [CHANGELOG](https://raw.githubusercontent.com/ealap/vscode-language-ttcn/master/CHANGELOG.md)

### Reference
[TTCN-3 Core Language Specification v4.10.1 ](http://www.etsi.org/deliver/etsi_es/201800_201899/20187301/04.10.01_60/es_20187301v041001p.pdf)