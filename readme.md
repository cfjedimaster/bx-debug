# bx-debug

This is the beginning of a simple debugging module for BoxLang, looking to recreate the Adobe ColdFusion feature where debugging information is appended at the end of a web page. This is *incredibly* early and shouldn't be used yet, so if you actually *do* use it, well, you've been warned. 

After the module is installed, you will get a BIF, `debugDisplay()`, that can be added to your templates to dump out debugging information. This could be done in `onRequestEnd` as an example.

I'll soon be adding `debugGet()` to retrieve the debug information for you to do whatever you want with it.

## Supported Debugging Information

* Templates and execution times
* Database queries

| Date | Change |
| ------ | ---------- |
| May 14, 2025 | Initial Release to GitHub |
