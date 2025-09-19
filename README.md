# .ft - Fungible Token Standard Container for BSV

## Overview

`.ft` is a standard file type container for all fungible token standards on the BSV blockchain. It provides a unified interface for working with various fungible token implementations including 1sat ordinals, STAS, and other token standards that exist or may emerge on BSV.

## Purpose

The `.ft` standard serves as a universal wrapper that can reference and contain any fungible token standard on BSV, providing consistency and interoperability across different token implementations. Whether working with 1sat ordinals, STAS tokens, or any other fungible token standard, `.ft` provides a common container format.

## Supported Token Standards

- 1sat ordinals
- STAS (Satoshi Token Asset Standard)
- Other BSV fungible token standards

## File Structure

`.ft` files act as containers that reference the underlying fungible token standard being used, along with relevant metadata and transaction information.

## Related Standards

- `.nft` - Non-fungible token container standard for BSV

## License

This project is licensed under the Open BSV License.

Copyright (c) 2024 Open BSV

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

1. The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

2. The Software, and any software that is derived from the Software or parts thereof,
can only be used on the BSV blockchains. The BSV blockchains are defined, for purposes of
this license, as the Bitcoin blockchain containing block height #556767 with the hash
"000000000000000001d956714215d96ffc00e0afda4cd0a96c96f8d802b1662b" and the test blockchains
that are supported by the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.