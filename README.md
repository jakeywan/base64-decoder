# base64-decoder
This will work for small strings, but for large, base64 encoded SVGs (my original intended use case) it runs out of gas fairly quickly. I think inline assembly is the only way to accomplish this gas-efficiently.

This is basically a fork of this code with some comments to clarify processes, and some apparently-extra stuff removed: https://github.com/BlockChainCaffe/Base64.sol
