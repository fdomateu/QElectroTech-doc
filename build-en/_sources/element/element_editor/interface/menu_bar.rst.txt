.. _element/element_editor/interface/menu_bar

=======================
Element editor menu bar
=======================

The framework and widget toolkit `Qt`_ allows the design of drop-down menus. The drop-down menus 
are a characteristic graphical control element from the desktop applications. Each of the drop-down 
menus contains a number of options to initiate an action. The Menu bar is placed at top from the main 
windows. The figure bellow shows how the menu bar from QElectroTech looks.

.. figure:: graphics/qet_elementeditor_menu.png
   :align: center

   Figure: QElectroTech Element editor Menu bar

As is showed at the figure, QElectroTech element editor bar contains the Menus ``File``, ``Edit``, 
``Display``, ``Settings`` and ``Help``.

File menu
~~~~~~~~~~

.. figure:: ../../../images/qet_element_editor_menu_file.png
   :align: center

   Figure: QElectroTech file menu 

+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Option                                 | Function                                                         | Keyboard shortcut         | Icon               |
+========================================+==================================================================+===========================+====================+
| New                                    | Creates a new Project                                            |   ``Ctrl + n``            | |project-new|      |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Open                                   | Opens an existing project                                        |   ``Ctrl + o``            | |project|          |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Open from a file                       | Opens an existing project                                        |   ``Ctrl + o``            | |project|          |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Starting the DXF converter pluging     | Opens an existing project                                        |   ``Ctrl + o``            | |project|          |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Recently opened                        | Saves the current project and all its folios                     |   ``Ctrl + s``            | |document-recent|  |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Save                                   | Saves the current project and all its folios                     |   ``Ctrl + s``            | |document-save|    |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Save as                                | Saves the current project with a different file name             |                           | |document-save-as| |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Save to a file                         | Exports the curret folio to another format                       |   ``Ctrl + Shift + x``    | |document-export|  | 
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Reload                                 | Print one or more folio of the current project                   |   ``Ctrl + p``            | |document-print|   |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+
| Quit                                   | Closes QElectroTech                                              | ``Ctrl + q``/ ``Alt + F4``| |application-exit| |
+----------------------------------------+------------------------------------------------------------------+---------------------------+--------------------+


+------------+------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
| Menu       | Options                            | Function                                                              | Keyboard shortcut         | Toolbar icon   |
+============+====================================+=======================================================================+===========================+================+
| **File**   | New                                | Creates a new Element                                                 |   ``Ctrl + n``            | |icon_new|     |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Open                               | Opens an existing element from a library                              |   ``Ctrl + o``            | |icon_open|    |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Open from a file                   | Opens an existing element from the disk                               |   ``Ctrl + Shift + o``    |                |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Starting the DXF converter pluging |                                                                       |                           |                |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Recently opened                    | Open an element from history (recently opened files)                  |                           |                |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Save                               | Saves the current Element changes (overwrites)                        |   ``Ctrl + s``            | |icon_save|    |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Save as                            | Saves the Element as a new element from a library                     |                           | |icon_save_as| |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Save to a file                     | Saves the Element as a different file on disk                         |   ``Ctrl + Shift + s``    |                |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Reload                             | Reloads the opened element (all changes which are not saved are lost) |   ``f5``                  | |icon_reload|  |
+            +------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+
|            | Quit                               |  Quits QElectroTech Element editor                                    | ``Ctrl + q``/ ``Alt + F4``|                |
+------------+------------------------------------+-----------------------------------------------------------------------+---------------------------+----------------+

Edit menu
~~~~~~~~~~

.. figure:: ../../../images/qet_element_editor_menu_edit.png
   :align: center

   Figure: QElectroTech edit menu 

+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
| Option                                     | Function                                                    | Keyboard shortcut         | Icon                  |
+============================================+=============================================================+===========================+=======================+
|  Undo                                      | Undoes the previous action                                  |  ``Ctrl + z``             | |edit-undo|           |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Redo                                      | Restores the undone action                                  |  ``Ctrl + y``             | |edit-redo|           |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Select All                                | Selects all elments on the folio                            |  ``Ctrl + a``             | |edit-select-all|     |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Select none                               | Deselect all elments on the folio                           |  ``Ctrl + Shift + a``     | |edit-select-none|    |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Invert selection                          | Inverts selection of elements                               |  ``Ctrl + i``             | |edit-select-invert|  |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Cut                                       | Puts selected elements into the clipboard                   |  ``Ctrl + x``             | |edit-cut|            |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Copy                                      | Copies selected elements                                    |  ``Ctrl + c``             | |edit-copy|           |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Paste                                     | Pastes elements from the clipboard into the folio           |  ``Ctrl + v``             | |edit-paste|          |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Paste in the area                         | Pastes elements from the clipboard into the folio           |  ``Ctrl + v``             | |edit-paste|          |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Paste from                                | Pastes elements from the clipboard into the folio           |  ``Ctrl + v``             | |edit-paste|          |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Delete                                    | Removes selected elements from the folio                    |  ``Del``                  | |edit-delete|         |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Edit name and information of the element  | Rotates selected elements and texts                         |  ``Space``                | |transform-rotate|    |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Edit author information                   | Rotates selected texts to a specific angle                  |  ``Ctrl + Space``         | |object-rotate-right| |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Edit element properties                   | Finds the selected element in the collections panel         |                           | |zoom-draw|           |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Bring to front                            | Brings the selection (s) to front                           |  ``Ctrl + Shift + Home``  | |bring_forward|       |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Raise                                     | Aproachs the selection (s)                                  |  ``Ctrl + Shift + Up``    | |raise|               |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Lower                                     | Moves away the selection (s)                                |  ``Ctrl + Shift + Down``  | |lower|               |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+
|  Send backwards                            | Sends in the backwards the selection (s)                    |  ``Ctrl + Shift + End``   | |send_backward|       |
+--------------------------------------------+-------------------------------------------------------------+---------------------------+-----------------------+

Display menu
~~~~~~~~~~~~

.. figure:: ../../../images/qet_element_editor_menu_display.png
   :align: center

   Figure: QElectroTech display menu 

+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+----------------------+
| Option                         | Function                                                                                   | Keyboard shortcut      |Icon                  |
+================================+============================================================================================+========================+======================+
| Zoom In                        | Expands the folio                                                                          |  ``Ctrl + +``          | |zoom-in|            |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+----------------------+
| Zoom Out                       | Shrinks the folio                                                                          |  ``Ctrl + -``          | |zoom-out|           |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+----------------------+
| Fit in view                    | Adjusts the zoom on exactly trhe part of the folio                                         |  ``Ctrl + 9``          | |view-fit-window|    |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+----------------------+
| Reset zoom                     | Restores default zoom level                                                                |  ``Ctrl + 0``          | |zoom-original|      |
+--------------------------------+--------------------------------------------------------------------------------------------+------------------------+----------------------+

Settings menu
~~~~~~~~~~~~~

.. figure:: ../../../images/qet_element_editor_menu_settings.png
   :align: center

   Figure: QElectroTech settings menu 

+--------------------------------+-----------------------------------------------------------+-------------------------------+----------------------+
| Option                         | Function                                                  | Keyboard shortcut             | Icon                 |
+================================+===========================================================+===============================+======================+
| Display                        | Displays or hides toolbars and panels                     |                               | |configure-toolbars| |
+--------------------------------+-----------------------------------------------------------+-------------------------------+----------------------+
| Full screen mode               | Displays QElectroTech in full screen mode                 |  ``Ctrl + Shift + f``         | |view-fullscreen|    |
+--------------------------------+-----------------------------------------------------------+-------------------------------+----------------------+
| Configure QElectroTech         | Allows to specify various parameters for QElectroTech     |                               | |configure|          |
+--------------------------------+-----------------------------------------------------------+-------------------------------+----------------------+

Help menu
~~~~~~~~~

.. figure:: ../../../images/qet_element_editor_menu_help.png
   :align: center

   Figure: QElectroTech help menu 

+-------------------------------------+---------------------------------------------------------------------------------------+---------------------------+-------------------+
| Option                              | Function                                                                              | Keyboard shortcut         | Icon              |
+=====================================+=======================================================================================+===========================+===================+
| What's This?                        | Enquires main menu options                                                            | ``Shift + f1``            |                   |
+-------------------------------------+---------------------------------------------------------------------------------------+---------------------------+-------------------+
| About QElectroTech                  | Displays information about QElectroTech                                               |                           | |qet-icon|        |
+-------------------------------------+---------------------------------------------------------------------------------------+---------------------------+-------------------+
| Online manual                       | Lauches the default browser to the online manual of QElectroTech                      | ``f1``                    | |help-contents|   |
+-------------------------------------+---------------------------------------------------------------------------------------+---------------------------+-------------------+
| Youtube channel                     | Lauches the default browser on the Youtube channel of QElectroTech                    |                           | |show-video|      |
+-------------------------------------+---------------------------------------------------------------------------------------+---------------------------+-------------------+
| Support the project with a donation | Lauches the default browser on the QElectroTech donation paypal account               |                           | |help-donate|     |
+-------------------------------------+---------------------------------------------------------------------------------------+---------------------------+-------------------+
| About Qt                            | Displays information about `Qt`_ library                                              |                           | |qt-icon|         |
+-------------------------------------+---------------------------------------------------------------------------------------+---------------------------+-------------------+

.. _Qt: https://www.qt.io/

.. |project-new| image:: ../../../images/ico/22x22/project-new.png
.. |project| image:: ../../../images/ico/22x22/project.png
.. |document-recent| image:: ../../../images/ico/22x22/document-open-recent.png
.. |document-save| image:: ../../../images/ico/22x22/document-save.png
.. |document-save-as| image:: ../../../images/ico/22x22/document-save-as.png
.. |project-close| image:: ../../../images/ico/22x22/project-close.png
.. |document-export| image:: ../../../images/ico/22x22/document-export.png
.. |document-print| image:: ../../../images/ico/22x22/document-print.png
.. |application-exit| image:: ../../../images/ico/22x22/application-exit.png

.. |edit-undo| image:: ../../../images/ico/22x22/edit-undo.png
.. |edit-redo| image:: ../../../images/ico/22x22/edit-redo.png
.. |edit-cut| image:: ../../../images/ico/22x22/edit-cut.png
.. |edit-copy| image:: ../../../images/ico/22x22/edit-copy.png
.. |edit-paste| image:: ../../../images/ico/22x22/edit-paste.png
.. |edit-select-all| image:: ../../../images/ico/22x22/edit-select-all.png
.. |edit-select-none| image:: ../../../images/ico/16x16/edit-select-none.png
.. |edit-select-invert| image:: ../../../images/ico/16x16/edit-select-invert.png
.. |edit-delete| image:: ../../../images/ico/22x22/edit-delete.png
.. |transform-rotate| image:: ../../../images/ico/16x16/transform-rotate.png
.. |object-rotate-right| image:: ../../../images/ico/16x16/object-rotate-right.png
.. |element-edit| image:: ../../../images/ico/16x16/element-edit.png

.. |bring_forward| image:: ../../../images/ico/22x22/bring_forward.png
.. |raise| image:: ../../../images/ico/22x22/raise.png
.. |lower| image:: ../../../images/ico/22x22/lower.png
.. |send_backward| image:: ../../../images/ico/22x22/send_backward.png
.. |zoom-in| image:: ../../../images/ico/16x16/zoom-in.png
.. |zoom-out| image:: ../../../images/ico/16x16/zoom-out.png
.. |view-fit-window| image:: ../../../images/ico/22x22/view-fit-window.png
.. |zoom-original| image:: ../../../images/ico/22x22/zoom-original.png
.. |configure-toolbars| image:: ../../../images/ico/16x16/configure-toolbars.png
.. |view-fullscreen| image:: ../../../images/ico/16x16/view-fullscreen.png
.. |configure| image:: ../../../images/ico/16x16/configure.png
.. |qet-icon| image:: ../../../images/ico/16x16/qet.png
.. |help-contents| image:: ../../../images/ico/16x16/help-contents.png
.. |show-video| image:: ../../../images/ico/16x16/kdenlive-show-video.png
.. |help-donate| image:: ../../../images/ico/16x16/help-donate.png
.. |qt-icon| image:: ../../../images/ico/16x16/qt.png