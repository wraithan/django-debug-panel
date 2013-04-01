Django Debug Panel
==================

Django debug toolbar but displays in the developer tools window.

Current Implementation Plan
---------------------------

Highest priority is putting together a stupid simple proof of concept that
takes header information and dumps it to a panel in Firefox. After that, it is
research time into what exactly django-debug-toolbar and rails_panel are
sending. Feature parity is the eventual goal, but getting a working example is
most important.



Prior Art
---------

* https://github.com/robhudson/djangobug (attempt from 4 years ago)
* https://github.com/dejan/rails_panel (working rail/chrome version)
* https://github.com/paulrouget/firefox-jsterm (adds panel to firefox devtools)
* https://github.com/disqus/nose-performance (performance stuff)
* https://github.com/django-debug-toolbar/django-debug-toolbar (original toolbar)
* https://github.com/dcramer/django-devserver (does interesting logging stuff)
* https://github.com/binaryage/firelogger (generic firebug thing)
* https://github.com/binaryage/firelogger.py (python plugin for the firelogger)
