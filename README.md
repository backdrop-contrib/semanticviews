Semantic Views
==============

The Semantic Views allows users to alter the default HTML output by the Views module without overriding template files. This means, for example, you can change a field from being wrapped by a `<span>` tag to being wrapped in a `<h2>` tag.

The module provides a Views style and row style plugin. These plugins ideally work together but can be used separately.

When properly configured, the Semantic Views style plugin can effectively replace Views' own unformatted, HTML List and Grid styles. The row style plugin can let help leverage your theme's other CSS styles more easily.

Installation
------------

Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules.


Configuration
-------------

1. Navigate to Administration > Functionality and enable Semantic Views, Views, and the Views UI modules.
2. Navigate to Administration > Structure > Views and next to the view to edit, select the "Edit" function.
3. In the "Format" fieldset, select the link next to "Format:" (by default it is set to Unformatted list). Select "Semantic Views" and Apply the changes.
4. Select the "Settings" link to view the available options.
5. The "Grouping Title" fieldset allows users to change Elements and Class Attributions when using groups. The view will insert the Grouping's Title Field.
6. The "List" fieldset provides choices for List types and Class attributions. Note: if the output is a HTML list, the row element should also be set to "li".
7. The "Row" fieldset provides choices for the row's Elements and Class attributions. The rows can also be defined by "First/Last every nth" and by "Striping class attributes".
8. Save any changes.

When properly configured, the Semantic Views style plugin can effectively replace Views' own unformatted, HTML List and Grid styles. The row style plugin can let help leverage your theme's other CSS styles more easily.

There is a demo semantic View that is automatically imported when the module is enabled to provide an idea of how to configure Views with semantic markup.

Issues
------

To submit bug reports and feature suggestions, or to track changes visit https://github.com/backdrop-contrib/semanticviews/issues.

Current Maintainers
-------------------

- Herb v/d Dool (https://github.com/herbdool/)
- Seeking additional maintainers.

Credits
-------

- Ported to Backdrop by Herb v/d Dool (https://github.com/herbdool/)
- Originally developed for Drupal by [Scyther](https://www.drupal.org/u/scyther)

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.