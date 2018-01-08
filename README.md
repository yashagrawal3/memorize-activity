What is this?
=============

Memorize is about finding matching pairs.  A pair can be images, sounds and text and this could be extended to animations or movie snippets as well.  Which pairs match is up to the creator of the game.  Memorize is more than a predefined game you can play, it allows you to create new games yourself as well.

How to use?
===========

Memorize is part of the Sugar desktop.  Please refer to;

* [How to Get Sugar on sugarlabs.org](https://sugarlabs.org/),
* [How to use Sugar](https://help.sugarlabs.org/),
* [How to use Memorize](https://help.sugarlabs.org/en/memorize.html)

How to upgrade?
===============

On Sugar desktop systems;
* use [My Settings](https://help.sugarlabs.org/en/my_settings.html), [Software Update](https://help.sugarlabs.org/en/my_settings.html#software-update), or;
* use Browse to open [activities.sugarlabs.org](https://activities.sugarlabs.org/), search for `Memorize`, then download.

How to integrate?
=================

On Debian and Ubuntu systems;

```
apt install sugar-memorize-activity
```

On Fedora systems;

```
dnf install sugar-memorize
```

Memorize depends on Python, GTK+ 3, GStreamer, [GStreamer espeak plugin](https://github.com/sugarlabs/gst-plugins-espeak), and the Sugar Toolkit.

Memorize is started by [Sugar](https://github.com/sugarlabs/sugar).

How to develop?
===============

* main program is `activity.py`,
* directory `demos` contains predefined games, as ZIP bundles of XML, with document type definition `memorize.dtd`,