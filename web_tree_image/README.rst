.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :alt: License: AGPL-3

=====================================
Display images and icons in tree view
=====================================

This module defines a tree image widget, to be used with either binary fields
or (function) fields of type character. Use ``widget='image'`` in your view
definition. Optionally, set a ``width`` attribute. Default width is 30px.

If you use the widget with a character field, the content of the field can be
any of the following:

* The absolute or relative location of an image. For example,
  "/<module>/static/src/img/youricon.png"

* A standard icon from the web distribution, without path or extension, For
  example, 'gtk-open'

* A dynamic image in a data url base 64 format. Prefix with
  'data:image/png;base64,'

Usage
=====

Set the attribute ``widget=image`` in a ``field`` tag in a tree view.
You can also set ``height=<height>`` to set the height the image will have.
Note that this just sets the CSS ``max-height`` attribute,
if you want to make the server return a resized, maybe to save data by making it
return a smaller one or to have uniform images, use the
``resize="<width>,<height>"`` attribute.

Credits
=======

Contributors
------------

* Stefan Rijnhart
* Leonardo Donelli <donelli@webmonks.it>
* Jay Vora <jay.vora@serpentcs.com>
* Meet Dholakia <m.dholakia.serpentcs@gmail.com>
* Nikul Chaudhary <nikul.chaudhary.serpentcs@gmail.com>

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
