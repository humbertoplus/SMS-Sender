SMS-Sender
==========

Send SMS from PC with usb modem

<img src="https://img.shields.io/badge/license-GPL%20v2-blue.svg" />

<img src="http://i.imgur.com/8sjZWqW.png" />

<h2><a name="dataf" class="anchor" href="#dataf"><span class="mini-icon mini-icon-link"></span></a>Data Format</h2>

```xml
<?xml version="1.0" encoding="UTF-8"?>
<root><sms id="0" phone="0000000000" loca="886">Mr. Gibbs, hi there..</sms><sms id="1" phone="0000000000" loca="886">Mr. Mcgee, hello.</sms></root>
```

<h2><a name="require" class="anchor" href="#require"><span class="mini-icon mini-icon-link"></span></a>Require</h2>
* Sqlite - http://www.sqlite.org/

<h2><a name="runtime" class="anchor" href="#runtime"><span class="mini-icon mini-icon-link"></span></a>Runtime</h2>
* sqlite3.dll
* CommonEx.dll

<h2><a name="build" class="anchor" href="#build"><span class="mini-icon mini-icon-link"></span></a>Build</h2>

- Download SQLite <a href="https://sqlite.org/download.html">here</a> (Source code and binary DLL)
- Download Pelles C <a href="http://www.pellesc.de/index.php?page=download&lang=en&version=8.00">here</a>
- Enable "Microsoft extensions" and "Undecorate exported __stdcall functions" options in Pelles C project settings
- Build it

<h2><a name="author" class="anchor" href="#author"><span class="mini-icon mini-icon-link"></span></a>Author</h2>
* 2014 rchockxm (rchockxm.silver@gmail.com)
