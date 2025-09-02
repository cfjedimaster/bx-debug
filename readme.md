# bx-debug

This is the beginning of a simple debugging module for BoxLang, looking to recreate the Adobe ColdFusion feature where debugging information is appended at the end of a web page. This is *incredibly* early and shouldn't be used yet, so if you actually *do* use it, well, you've been warned. 

After the module is installed, you will get a BIF, `debugDisplay()`, that can be added to your templates to dump out debugging information. This could be done in `onRequestEnd` as an example.

You also get `getDebugInfo()` which returns the debug info in a raw structure.

## Supported Debugging Information

* Templates and execution times
* Database queries
* HTTP timings and size

| Date | Change |
| ------ | ---------- |
| September 2, 2025 | Added current application name and session count. |
| September 2, 2025 | Added settings that will mark items that take too much time. |
| September 1, 2025 | I had not committed in a while, but HTTP is supported now, as well as getDebugInfo |
| May 14, 2025 | Initial Release to GitHub |
