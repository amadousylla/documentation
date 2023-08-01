=====
Menus
=====

Menus are used to organize your website’s content effectively and help visitors navigate through
your web pages effectively. User-friendly and well-structured website menus also play a crucial role
in improving :ref:`search engine rankings <.

Odoo allows you to customize the content and appearance of these menus to your needs.

Menu editor
===========

To customize your website's menu, go to :menuselection:`Website --> Site --> Menu Editor`. From
there, you can:

- rename a menu item or change its URL using the :guilabel:`Edit Menu Item` icon.
- delete a menu item using the :guilabel:`Delete Menu Item` icon;
- move a menu item by drag and dropping it to the desired place in the menu;
- make an existing menu item the sub-menu of another item by drag and dropping it to the right,
  underneath its parent menu. The parent menu then becomes a drop-down menu.

.. image::
   :alt: Menu editor with sub-menus

To create a menu item, click :guilabel:`Add Menu Item`, then, in the pop-up window that appears on
the screen, enter the :guilabel:`Name` and :guilabel:`Url` of the related page. Click :guilabel:`OK`
to create the menu item.

.. note::
  - Type `/` in the :guilabel:`URL` field to search for an existing page of your website.
  - By default, pages are added to the menu when :doc:`they are created <../pages>`.
  - You can also access the menu editor by clicking :guilabel:`Edit`, then selecting any menu item
    and clicking the :guilabel:`Edit menu` icon.

   .. image::
      :alt: Edit menu icon when you click on a menu item

To edit a link, go to the menu editor and click the edit button, or click Edit, select the menu item
and click the Edit link button.

This is also where you can duplicate a link and access the menu editor

same for mega menus : you can copy link, edit link, remove link


Mega menus
----------

Mega menus are similar to drop-down menus, but instead of a simple list of sub-menus, they display a
panel divided into groups of navigation options. This makes them suitable for websites with large
amounts of contents, as they can help include all of your web pages in the menu, while still making
all menu options visible at once. Mega menus can also be structured more visually than regular
drop-down menu items, for example through layout, typography and icons.

To create a mega menu, go to :menuselection:`Website --> Site --> Menu Editor`, click
:guilabel:`Add Mega Menu Item`, then enter a :guilabel:`Name`, and click :guilabel:`OK`.

You can then customize the mega menu's options and layout. To do so, click the mega menu in the
navigation bar, then click :guiabel:`Edit`.

.. image:: menus/mega-menu.png
   :alt: Mega menu item in the navigation bar.

Each menu option is an individual building block, which means you can edit its text directly in the
related block and format it using the :guilabel:`Customize` tab in the website builder.

You can also duplicate, delete or edit a link by clicking the corresponding icon on the menu option.
The link is defined in the Inline text section of the website builder. Type `/`to search for a page
or `#` to link to a custom anchor.



Customization
=============

Menu items and mega menus can be :ref:`customized <website/customization>` according to your website
needs and style. When in **edit mode** click on a menu or mega menu items to change the appearance,
URL, etc.

To adapt the general appearance of the mega menu,
go to the the :guilabel:`Mega menu` in the website builder and select the desired
:guilabel:`Template` and the :guilabel:`Size`.
