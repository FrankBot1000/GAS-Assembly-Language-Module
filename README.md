# GAS-Assembly-Language-Module
A Barebones BBEdit/TextWrangler Codeless Language Module for reading GAS/AT&amp;T Assembly

For both 32- and 64-bit code. Feel free to suggest changes.

Installation:

For BBEdit, copy the GAS Assembly.plist file to:
~/Library/Application Support/BBEdit/Language Modules/

For TextWrangler, copy the GAS Assembly.plist file to:
~/Library/Application Support/TextWrangler/Language Modules/

Restart BBEdit or TextWrangler.




Additional Notes:

For the GAS Assembly.plist file:
assembly directive syntax coloring is based on the BBLMPredefinedNameList.
assembly instruction syntax coloring is based on the BBLMKeywordList.
Single line coloring of comments. Block commenting sometimes omits the first "/*" unless you scroll back over it.
Number values are colored, but registers and function names remain uncolored.
