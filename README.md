# Google Tasks AHK `.exe`

Simple wrapper around `chrome.exe` that opens the standalone Google Tasks view (available in Google Calendar).
It starts as separate process to avoid grouping the the window with any available Google Calendar windows already open on the desktop.
Also it uses a custom icon, since by default Google Calendar's icon would be use when creating an _app_ from the page in Chrome.