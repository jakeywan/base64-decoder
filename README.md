# base64-decoder
This will work for small strings, but for large, base64 encoded SVGs (my original intended use case) it runs out of gas fairly quickly. I think inline assembly is the only way to accomplish this gas-efficiently.
