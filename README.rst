Django Debug Panel
==================

Django debug toolbar but displays in the developer tools window.

Current Implementation Plan (For Firefox)
-----------------------------------------

Highest priority is putting together a stupid simple proof of concept that
takes header information and dumps it to a panel in Firefox. After that, it is
research time into what exactly django-debug-toolbar and rails_panel are
sending. Feature parity is the eventual goal, but getting a working example is
most important.

Google Chrome
-------------

I don't plan on implementing this but I do plan on documententing everything
that the server will be sending. This way someone else can build the Chrome
version. If you are interested in this, let me know and we can colaborate on
the middleware and make sure releases happen in lock step if they are backwards
incompatible.

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
