# __Apperçu général__ #

A l'ouverture de Pinta vous noterez que son environnement est très épuré, comprable à MS Paint, avec plus de fonctionnalités avancées.

![Environnement](img/overview/workspacetools.png)

## __Environnement Pinta__ ##
[__Barre de menu__](#menu-bar-features) - Menus déroulants.

![menubar](img/overview/menubar.png)

[__Barre d'outils__](#toolbar-features) - Contient des boutons et autres éléments pouvant être utilisés pour éxecuter des actions.

![toolbar](img/overview/toolbar.png)

[__Menu outils__](#tools-menu-features) - Contient des groupes d'icones ou boutons permettant d'accéder rapidement aux fonctionnalités. Fonctionne avec le menu réglage d'outils permettant d'ajuster pes propriétés des outils.

![tools](img/overview/tools.png)

[__Menu palette__](palette.md) - Accès rapide aux préréglages des couleurs. Sélectionnez la couleur de premier plan ou de second plan avec un clic gauche ou droit sur la couleur de votre choix.

![palette](img/overview/palette.png)

[__Fenêtre des calques__](layers.md) - Afiche le nombre des calques et le calque actif. Dans Pinta, les calques peuvent être transparent, translucides ou opaques, être visible dns l'espace de travail ou non.

![layers](img/overview/layers.png)

__Fenêtre image__ - Affiche les images ouvertes, utilisables comme calque ou comme image de base.

![images](img/overview/images.png)

[__Fenêtre historique__](setup.md#Using-Undo-or-Redo-Functions) - Affiche la liste des opérations ou commandes effectuées. Peut être annulée ou répétée en sélectionnant la commande dans la liste.

![history](img/overview/history.png)

## __Barre de menu__ ##

![menu](img/overview/menubar.png)
__Fichier__ - contient les commandes permettant de créer une nouvelle image, une capture d'écran, ouvrir, enregistrer ou fermer une image et fermer Pinta.

![file](img/overview/file.png)

__Editer__ - Contient les propriétés relatives à la manipulation des images et des information des images. Pour accélerer la navigation et l'exécuton des commandes, chaque commande en dehors de la palette dispose de raccourcis [raccourcis](shortcuts.md).

![edit](img/overview/edit.png)

__Affichage__ - Contient des commandes permettant de modifier l'affichage des éléments de l'espace de travail. Ces commandes ne modifient pas l'image.

![view](img/overview/view.png)

__Image__ - Contient des commandes modifiant l'image. La plupart dess réglages d'images disposent de touches de raccourcis [shortcuts](shortcuts.md). Les commandes disposant de points de suspension "..." ouvrent une fenêtre pop-up permettant de configurer la fonctionnalité.

![image](img/overview/image_menu.png)

[__Calques__](layers.md) - Contient des commandes qui n'affectent que le calque actif, en surbrillance dans la fenêtre des calques. Permet d'accéder au menu des propriétés des calques et de définir le type de contenu que celui-ci contiendra.

![layers](img/overview/layers_menu.png)

__Réglages__ - Contient des commandes modifiant la colorisation des pixels du calque actif. Dispose de touches de raccourcis [shortcuts](shortcuts.md).

![adjustments](img/overview/adjustments.png)

[__Effets__](effects.md) - Contient des commandes permettant d'ppliquer un effet à une sélection dans un calque ou à un calque entier. Le menu Effets est composé de sept sous-menus.

![effects](img/overview/effects.png)

<!-- Addins are disabled as of Pinta 2.0 due to Mono.Addins missing support for .NET 6 / GTK 3. See https://bugs.launchpad.net/pinta/+bug/1998928
__Add-ins__ - will allow you to install more effects, adjustments, and tools via the Add-in Manager. The Add-In Manager provides an easy way to manage any plugins or extensions you might have installed.

![addins](img/overview/addins.png)
-->

__Window__ - has two commands. Below those commands you'll notice an image name for each image that you currently have open. A dot will be displayed to the left of the active image. You can switch between images using the shortcut keys `Alt` + `1` for image one, `Alt` + `2` for image two, `Alt` + `3` for image three, and etc. The image names listed in the Window menu will be the same names that are listed in the Images Window.

![window](img/overview/window.png)

[__Help__](index.md#help) - provides quick access to a number of online resources like the [Pinta Website](https://www.pinta-project.com/), [File a Bug](https://github.com/PintaProject/Pinta/issues), [Translate This Application](https://hosted.weblate.org/engage/pinta/), and About.

![help](img/overview/help.png)

## __[Toolbar Features](#general-overview)__ ##

![toolbar](img/overview/toolbar.png)

![New](img/overview/new.png) __New__ - command allows you to create a new, blank, single-layered image.

![Open](img/overview/open.png) __Open__ - command allows you to open an existing image for editing.

![Save](img/overview/save.png) __Save__ - command allows you to save the image with the current file name.

![Cut](img/overview/cut.png) __Cut__ - command allows you to remove a selected portion of the active layer and place it on the clipboard (a clipboard is a temporary storage area for data that the user wants to copy from one place to another).

![Copy](img/overview/copy.png) __Copy__ - command duplicates the selected region to the clipboard. Unlike the Cut command, the Copy command leaves the selection on the active layer. The current selection also remains active in the active window.

![Paste](img/overview/paste.png) __Paste__ - command allows you to insert an image or a selected section of a layer from the clipboard into the active layer.

![Undo](img/overview/undo.png) __Undo__ - command allows you to erase the last change done to a project, reverting it to an older state. Notice the History Window when you click on the Undo command - the selected item moves up the list to the previous item.

![Redo](img/overview/redo.png) __Redo__ - command allows you to reverse your last Undo. Notice the History Window when you click on the Redo command - the selected item moves down the list to the next item. So the Redo command restores any actions that have been previously undone using an Undo.

![Crop to Selection](img/overview/crop.png) __Crop to Selection__ - command is only available to a selected part of an image. To see how this feature works, click the Rectangle Select button on the Tool Palette and then select an object in your image.

![Deselect All](img/overview/deselect.png) __Deselect All__ - command forces all selected pixels to be deselected. After you use this command, you'll have no pixels in the active window selected.

![Zoom](img/overview/zooming.png) __Zoom__ - command gives it the appearance of magnifying it or moving away from the image. You can use the drop-down menu to select a specific percentage zoom setting.

![Cursor Indicator](img/overview/cursor.png) __Cursor Indicator__ - to show pixel coordinates where the computer cursor is located on the image.

![Selection Indicator](img/overview/selection.png) __Selection Indicator__ - to show the pixel area of the selection.

## __Tools Menu Features__ ##

![tools](img/overview/toolsname.png)

Each item in the **Tools Menu** can be hovered over to view a tooltip with detailed information on the available mouse and keyboard actions when using the tool.

![Rectangle Select](img/overview/recsel.png) __Rectangle Select__ - used to select portions of the project in a rectangle shape. When a portion of a project is selected, tools that are used will only work in the selected area of the project. If a square selection is needed, hold the `Shift` key when selecting the area. Holding down the left-click button on your mouse to select and holding down the right-click button on your mouse to deselect.

![Lasso Select](img/overview/lasso.png) __Lasso Select__ - used to custom select which sections of the project you want selected. This is done by drawing around the portion of the project you want selected while holding down the left-click button on your mouse.

![Ellipse Select](img/overview/ellsel.png) __Ellipse Select__ - works the same way as the Rectangle Select except it selects in an elliptical shape. Like the Rectangle Select, if you hold the `Shift` key, it will select a circular shape instead of an ellipse.

![Magic Wand Select](img/overview/wand.png) __Magic Wand Select__ - used to select sections of the image that are similar. This tool can be adjusted to grab more or less of the image that resembles where it was used.

![Paint Bucket](img/overview/bucket.png) __Paint Bucket__ - used to fill areas of similar color with another solid color.

![Paint Brush](img/overview/brush.png) __Paint Brush__ - used to make free-hand inking and painting on the layer. This tool can be customized using the Palette and the Tools Settings Bar to change its properties.

![Pencil](img/overview/pencil.png) __Pencil__ - used to make free-hand pencil marks on the layer that are 1 pixel in size.

![Clone Stamp](img/overview/clone.png) __Clone Stamp__ - used to select a section of the layer that will be replicated into another section. This can be useful for eliminating troublesome sections that has multiple colors, patterns, or textures as it will replicate those section and place them in the layer.

![Text](img/overview/text.png) __Text__ - used to add text to the project. This tool has the option to change the font with any font loaded on your computer as well as the font color in the Tools Settings Bar.

![Rectangle](img/overview/rec.png) __Rectangle__ - used to create rectangles that can be either outlined or filled shapes. If you hold the `Shift` key, it will create a square shape instead of a rectangle.

![Ellipse](img/overview/ell.png) __Ellipse__ - used to create elliptical shapes that can be either outlined or filled shapes. Like the rectangle tool, if you hold the `Shift` key, it will create a circle shape instead of an ellipse.

![Move Selected Pixels](img/overview/movepix.png) __Move Selected Pixels__ - used to move or rotate a selected section of the project, and to move or rotate layers of the project. To move, hold down the left-click button on your mouse to drag the selection or layer around. To rotate, hold down the right-click button on your mouse to turn the selection or layer around.

![Move Selection](img/overview/movesel.png) __Move Selection__ - used to move or rotate the selection itself. To move, hold down the left-click button on your mouse to drag the selection around. To rotate, hold down the right-click button on your mouse to turn the selection around.

![Zoom](img/overview/zoom.png) __Zoom__ - used to view the project being worked on more closely. After selecting this tool, click on the section of the image you wish to view more closely.

![Pan](img/overview/pan.png) __Pan__ - used to move around in the project workspace when the area being worked on is larger than the screen. To use this tool, click in an area (the best area to select is somewhere in the middle of the workspace project) then hold down the left-click button on your mouse and move the hand around. The image will move as if you grabbed the image where you clicked, and push or pull the project in the direction that you moved the hand.

![Gradient](img/overview/gradient.png) __Gradient__ - used to create a gradual blend between the primary and secondary color from the palette. Hold down the right-click button on your mouse to reverse the primary and secondary color gradient blend.

![Eraser](img/overview/eraser.png) __Eraser__ - used to remove parts of a layer. When used on a bottom layer, it will leave a transparent background. When used on a layer other than the bottom will leave a hole in the layer that will show the next underlying layer.

![Color Picker](img/overview/picker.png) __Color Picker__ - used to select a color from the image or layer you are working on.

![Recolor](img/overview/recolor.png) __Recolor__ - used to replace the primary color with the secondary color. Hold down the right-click button on your mouse to reverse the secondary for the primary color.

![Line/Curve](img/overview/line.png) __Line/Curve__ - used to create either straight or curved lines. To customize the line, change the tool properties in the Tools Settings Bar.

![Rounded Rectangle](img/overview/roundrec.png) __Rounded Rectangle__ - is similar to the rectangle tool except it creates rectangles with rounded corners.

![Freeform Shape](img/overview/freeform.png) __Freeform Shape__ - use to create irregular shapes that can be either outlined or filled shapes.
