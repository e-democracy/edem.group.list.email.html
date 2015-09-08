==============================
``edem.group.list.email.html``
==============================
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
E-Democracy customization of HTML-formatted messages in a group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

:Author: `Michael JasonSmith`_
:Contact: Bill Bushey <bill.bushey@e-democracy.org>
:Date: 2015-09-08
:Organization: `E-Democracy`_
:Copyright: This document is licensed under a
  `Creative Commons Attribution-Share Alike 3.0 License`_
  by `E-Democracy`_.

Introduction
===========

E-Democracy customizations to the HTML-formatted messages of a
`GroupServer`_ group are quite extensive: there are no HTML
formatted messages, just plain-text.

This product supplies the
``edem.group.list.email.html.message.EDemHTMLMessagePart`` class,
which has ``self.show = False`` set, so the HTML-version is not
shown.

Resources
=========

- Code repository: https://github.com/e-democracy/edem.group.list.email.html
- Questions and comments to http://groupserver.org/groups/development
- Report bugs at https://redmine.iopen.net/projects/edem

.. _GroupServer: http://groupserver.org/
.. _E-Democracy: https://e-democracy.org
.. _Bill Bushey: http://groupserver.org/p/wbushey
.. _Creative Commons Attribution-Share Alike 3.0 License:
   http://creativecommons.org/licenses/by-sa/3.0/
