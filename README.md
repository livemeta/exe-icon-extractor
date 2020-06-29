# exe-icon-extractor

This is a fork of [inithink/exe-icon-extractor](https://www.npmjs.com/package/@inithink/exe-icon-extractor)

I encountered some problems with @inithink package but couldn't find a way to contact him or the of the project so I created this package temporaly to fix the issues and make tests in case of someone needs it.

Usage:
```
const {extractIcon} = require('@inithink/exe-icon-extractor');
const buffer = extractIcon("C:\\Windows\\System32\\cmd.exe", "large");
 
const fs = require('fs');
fs.writeFileSync('cmd.ico', buffer);
```
