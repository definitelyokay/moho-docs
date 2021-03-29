------------------------------------------------------------------- 
Moho® 13 by Smith Micro Software Inc.
------------------------------------------------------------------- 

Thank you for purchasing Moho® 13 by Smith Micro Software, Inc.! This readme includes important information about your new software, some of which is not included in other documentation. Smith Micro Software, Inc. is committed to creating stable and functionally rich software tools.


------------------------------------------
Contents
------------------------------------------

- New Features

- Bug Fixes

- Additional Notes

- Known Issues

- Important Information

- System Requirements

- Technical Support

- The Smith Micro Commitment

- Content Distribution

- Copyright & Trademark Notice


------------------------------------------
New Features
------------------------------------------

Bitmap Freehand Brush Tool
Moho now has bitmap drawing capabilities! Texturize your characters and objects right in Moho using one of Moho’s default brushes or create a custom brush using the new Brush Manager if you’re a Moho Pro user.

Custom Bitmap Brush Creation (Pro Only)
Give your animation the style you want right in Moho by creating custom bitmap brushes. Create brushes with the look and behavior you need for your project by editing a variety of brush settings within Moho Pro’s bitmap Brush Manager. 

Exporting/Importing Bitmap Brushes
Share your custom bitmap brushes with others and across devices. Importing/exporting is done using the Brush Manager if you’re a Moho Pro user, or manually placing the brush files in your Custom Content folder if you’re a Moho Debut user. 

Bitmap Fill Bucket Tool
Quickly fill and color large areas of pixels for a speedy workflow when creating backgrounds or altering the color of an image layer texture. 

Blending Modes for Bitmap Tools
Create unique textures and effects while using the new bitmap Brush or Fill Bucket tool by changing their blending mode. Choose from a selection of over 15 modes. 

Bitmap Frame by Frame Capabilities
Create traditional style animations directly in Moho by combining the new Moho bitmap tools and image-based Frame by Frame layer. Speedup your workflow by creating a storyboard or animatic right in Moho.

New Actions Window (Pro Only)
Quickly cut through the clutter of a complex project by using the new Actions window. Search for actions using keywords, create tags for your actions, and organize your actions in groups.

3D Objects Light Manipulation (Pro Only)
Bring greater cohesion between your 2D and 3D assets within Moho by adjusting your imported 3D object’s lighting source, ensuring both 2D and 3D objects have a matching perspective. 

3D Objects Material Properties (Pro Only)
Get the look that fits your project best out of your imported 3D objects with new material editing options and toon shading controls. 

New Professional Quality Characters
Kickstart your project by using one of Moho’s new characters made by animation industry professionals. Explore their rigs, movements, and surrounding scene to learn new techniques and get inspiration. 


------------------------------------------
Bug Fixes
------------------------------------------

---------------
MOHO 13.0.1
---------------

•	Moho now scans for all available MP4 encoders to ensure that exporting to MP4 no longer fails if the first selected encoder is unavailable.
•	When applying a Layer Settings change to multiple Image layers at the same time, the Source Image of the layer no longer changes for all the Image layers. This is also corrected for material files for 3D Object layers.
•	When you use the Duplicate Frame button for an Image based Frame by Frame layer, the duplicated frame is no longer linked to the original and drawing on the duplicated frame will not impact the original. 
•	Using the Frame by Frame buttons of New Frame, Delete Frame, and Duplicate Frame is now recognized as a change in the project and thus becomes savable. 
•	When you select a bone, all associated Smart Bone actions are highlighted in the actions list.
•	When you create an action, it’s timeline is automatically opened.
•	When you select a layer, all actions that do not have a keyframe that applies to the selected layer will be grayed out in the actions list.
•	Moho no longer crashes when manually closing a vector object after a timeline point transformation, while having Auto-Fill set to on. 
•	Moho Debut no longer crashes when changing certain settings in the Export Animation window.
•	Moho no longer crashes when importing the selected layer into the last folder of a custom content folder within the Library.
•	Moho no longer crashes when you use the Point Reduction tool on objects created with the Scatter Brush.
•	Moho no longer crashes when auto save is on and a project with “inherited” Styles is closed.
•	Moho no longer crashes when you import an object and then immediately try to undo & redo the importing operation.
•	Moho no longer crashes in certain situations when using the Text tool to create a new text layer.
•	The top left corner of the Timeline window is now responsive when you drag Moho to a second display that is on the right of the main one. The lack of responsiveness was only noticeable when using a Frame by Frame layer due to the buttons that appear in this location, or when using a Wacom due to the Multitouch checkbox that appears.
•	Moho no longer crashes when doing multiple quick clicks of the Search button within the Library window
•	Moho no longer crashes when importing a custom folder into the Library and that folder was already imported. An alert now shows up that informs you the folder already exists within the Library.
•	Smart Bone actions associated to an imported reference layer are properly recovered after they are deleted, and Update Layer Reference is performed.
•	All image layers are now preserved when saving a file that was recovered after a crash.
•	“Duplicate as PNG” is now available in the right-click context menu of Image layers within Moho Debut.
•	When doing a Gather Media operation after using the bitmap tools on an image layer (and you don’t save the project) the gathered PNG files will have the changes you made even though you didn’t save the project. 
•	The custom content scene “CK The Quick and the Dead” now imports properly.
•	Moho no longer crashes on Mojave after docking/undocking, closing/opening, re-docking, and then changing the order of the actions in the list.
•	Moho no longer crashes when drawing with the blob brush while being extremely zoomed out in the workspace.
•	Moho no longer crashes when trying to apply a Smart Warp to a Video layer.
•	Moho no longer crashes when you delete an Image Sequence layer and perform enough operations to push the Image Sequence deletion operation out of the undo/redo history. 
•	When creating an image layer and you change the values in the Height or Width text boxes, the number you entered is now recognized when you use the mouse to click on “Create”. Before, it required you to either press Enter on your keyboard or click inside of the other text box. 
•	When importing a broken 3D object, the alert message now displays the full reason for the error.
•	A missing file warning is no longer presented randomly when using the Character Wizard to generate random characters. 
•	Exporting an action, deleting it, and then importing it now works properly.
•	The slider for distance in the Light window no longer gets stuck at the 100% mark when manually entering a value that’s greater than 100% and the starting point was less than 100%.
•	The Light window now refreshes its layout properly after being undocked.
•	The light widget now updates accurately to changes made to the various properties after the Light window is undocked and redocked.
•	You can now adjust the width of the right panel after you undock the Style window and you have the Action, Bitmap Color, and/or Light window docked. 
•	File > Export > Export OBJ now works properly, which means it creates an OBJ file out of a vector layer that has 3D Options turned on. 
•	Vector layers that have 3D Options turned on now display properly in the workspace when GPU Acceleration is turned on. 
•	Importing Moho 12 files into Moho 13 now properly loads actions associated with the following properties: Crayon effect, Gradient effect, Halo effect, Shaded effect, Shadow effect, Styles, and Video Tracking Points. 
•	When the Layers window is not docked, all right panel docked windows now properly resize when Moho is dragged to an additional display that has a different resolution. 
•	Using the mouse scroll wheel to change the value of Opacity for the Bitmap Eraser tool now changes the value by increments of 1.0, matching up to the behavior of other similar properties. 
•	The Action window’s docking status is now indicated even when it is closed, just like all other windows. 
•	Importing actions now have a non-zero timestamp, which means they respond to Chronological sorting. The timestamp logic is as follow:
		o	Importing a Moho 13 created action has a timestamp based on the originally created time of the action. 
		o	Breaking the imported action reference creates a timestamp of “now”.
		o	Opening a Moho 12 file in Moho 13 will set the timestamps for all actions within the project to the creation timestamp of the Moho 12 file.


---------------
MOHO 13.0.0
---------------

•	Exiting full screen mode no longer forces the Action window to redock
•	Moho no longer crashes if you have Action window docked and you enter & exit full screen mode
•	Moho no longer crashes when you connect a Wacom tablet without having the Wacom drivers installed.
•	Moho no longer crashes when a Frame by Frame layer is expanded and you use the Delete Frame button to delete the first frame
•	Scripting, if you call the CountSelectedLayers function with a group as argument, it now returns the number of selected layers present only in that group (Mantis 39806)
•	Re-linking an image sequence that was moved to another directory now works (Mantis 39584)
•	Switch layers nested in a main bone layer now work when the main bone layer has motion blur with sub-frame turned on.
•	An image sequence that has been moved to another directory can now be re-linked. (Mantis 39584)
•	When you have a single vector point selected that has an animation along the “Select Point Curvature” timeline channel, 
        double clicking the “Select Point Curvature” channel icon in the Motion Graph now displays associated keyframes
•	When you have a single vector point selected, you can now unmute any muted timeline channels associated with it in the Motion Graph
•	In a multi display setup alerts, warnings, and dialog boxes now display on the same screen that the main Moho window is on
•	Ctrl/Command + A now selects all text in a text boxes
•	Text cursor no longer randomly jump out of text boxes – this was caused by the text boxes losing focus during autosave
•	Using Ctrl + Up/Down arrow now stops at the bottom or top of the shapes stack (Mantis #39808)
•	Bezier handles now flip when attached to a pin bone after the pin bone is flipped (Mantis #39803)
•	When using multiple screens, File menu now displays on the same screen that the Moho window is on
•	Muting the “Audio Level” timeline channel of an Audio layer now ignores any keyframes on that channel (Mantis 39801)
•	Artifact keyframes no longer appear in the timeline when an animation automatically restarts, and the timeline cursor jumps back to frame zero


------------------------------------------
Additional Notes
------------------------------------------

---------------
MOHO 13.0.1
---------------

•	When closing the Bitmap Brush Manager and there are unsaved changes, the alert now gives you the option to Save (and exit), Discard (and exit), or Cancel (return to Brush Manager).
•	If you try to install Moho 13 on a device that doesn’t support OpenGL 4.1 an alert will appear informing that you cannot install Moho. 
•	Removed “Other Popular Scripts” link from the “Scripts” menu, the website is no longer operational
•	Moho now performs faster when you are zoomed in on an image and using the Bitmap tools.
•	The “Toggle Legacy Curves” script was removed since the ability to toggle this is part of the Layer Settings within the Vectors tab. 
•	Added an alert when trying to upload a corrupted image file, in all scenarios.


---------------
Moho 13.0.0
---------------

•	New dockable Bitmap Color window has been added to control the color of bitmap tools, the color of bitmap tools is not controlled by the Fill or Stroke color within the Style window.
•	Creating a new image layer now has a new workflow, you have the option to import a file or create a blank image layer. If you create a blank image layer Moho creates an associated PNG. 
        For an unsaved project the PNG is a temp file, for a saved project the location of the PNG is in the same directory that the project is saved in – temp file PNGs are moved to the directory. 
        When the project is saved, the content of the PNG file is updated to match up with the content of the image layer.
•	When you use the Duplicate Layer button on an image layer, the duplicate layer will reference the same PNG as previous version of Moho do. 
        Due to the new bitmap drawing capabilities, Moho now also allows you to duplicate certain image layers and the associated PNG. 
        This can be done via the new “Duplicate as PNG” option in the right-click context menu of certain image layers. 
•	Added a “Layers to PNGs” option when importing a PSD, which converts the layers of the PSD being imported into a set of new PNGs that Moho will use instead of the source PSD project.
•	Image layers that are referencing a PSD now have a “PSD” icon.
•	Default bitmap brushes cannot be edited, but their duplicates can be edited.
•	New Custom Content sub-folder has been added to store custom bitmap brushes, “Bitmap Brushes”. Previously existing “brushes” sub-folder has been renamed to “Vector Brushes”. 
•	When you have an image layer the command Edit > Clear now clears the content of the image layer.
•	GPU Acceleration is now OFF at default and has been labeled an “Experimental” feature.
•	Ability to import a Poser scene has been removed.
•	Removed the “Masking” tool from the Special tools section of the Tool Bar.
•	Removed the “Trace Image” (Draw > Trace Image) capability.
•	Removed ability to directly upload to Facebook and YouTube from Moho.
•	MOV video importing and exporting is now only available on Mac.
•	Updated to Wacom Multi-Touch API 4.0.
•	Updated to OpenGL 4.1.
•	Importing 3D objects has a new workflow, it’s done by creating a the newly added 3D Object layer.
•	The ability to manipulate 3D objects directly with bones has been temporarily removed. You can still use a combination of Smart Bones and Layer tools to manipulate the new 3D Object layer.
•	Moho Debut does not accept 3D objects when a Moho Pro project is being opened or imported in Debut. 
        If the Moho Pro project only has 3D Object layer it will be considered an invalid project, if the Moho Pro project also has other types of layers they will be loaded. 
•	File > Gather Media now collects OBJs, material files, and texture files. 
•	Default settings for Draw Freehand tool have been changed to
		o	Auto-weld: OFF
		o	Trim Start: Checked but disabled
		o	Trim End: Checked but disabled
		o	Weld Ends: ON
		o	Auto close: OFF
		o	Auto-fill: OFF
		o	Auto-stroke: ON
		o	Merge strokes: ON
		o	Hide auto-closed segments: Checked but disabled
		o	Variable line width: Use pen pressure
		o	Width variation %: 75
		o	Taper start: OFF
		o	Taper end: OFF
		o	Smoothing: 1
		o	Point reduction: 50
•	Changed default shortcuts to help create consistency between key combination for opening/closing a window and docking/undocking the same window. 
        Key combination for docking/undocking windows that can be docked is now Alt + the key combination to open/close that window. New open/close combination are:
		o	Layer Comps: Ctrl + Shift + J
		o	Timeline: Ctrl + Shift + W
		o	Styles: Ctrl + Shift + Y
		o	Actions: Ctrl + Shift + M
		o	Library: Alt + L
•	Other shortcut changes include:
		o	Refresh Media: Alt + Ctrl + M
		o	General Import: Alt + Ctrl + Y
		o	Use Selected Bones for Flexi Binding: Alt + Ctrl + F
		o	Reload Tools and Brushes from: Alt + Shift + Ctrl + R
		o	Show Documents Tab: Alt + Ctrl + J


------------------------------------------
Known Issues
------------------------------------------

•	Sometimes the Switch Selection Window can shrink too small to be usable. To fix that, just select another layer and then select the switch or frame by frame layer again.
•	Audio and Flash export; When exporting to Flash, the audio you embed in the Flash file must already be in MP3 format.
•	You can only have one audio track if you're planning to export a Flash movie. Because Moho can't encode MP3 files, it also can't mix down multiple audio streams into a single MP3 file. If you're targeting Flash, we recommend that you mix down multiple tracks and encode as MP3 prior to import into Moho.
•	EPS VS. Adobe Illustrator as an import choice; We recommend Illustrator as an import file format over EPS provided that the file being imported is Illustrator 8 or earlier compatible. Only import EPS if you have an EPS file. The preferred format, if available, is SVG over both EPS and Adobe Illustrator formats.
•	64-bit Windows does not support QuickTime. As such, there are import and export limitations with the .mov format. While the application supports the import of .mov files that use a general codec (like H.264 or AAC) by using the Windows Media Foundation library, other QuickTime specific codecs are not supported. Also, QuickTime allows for the import of audio formats like .mid, .midi, .m4p and .m4b.  
•	When exporting a QuickTime movie with alpha channel on Mac OS, the resulting movie always has a premultiplied alpha channel, regardless of the checkbox that says "Do not premultiply alpha channel."
•	If you don't want any cropping, select a preset that does not include a resolution in its name.
•	On Mac, exports using the "QuickTime (PNG-AAC)" output format always ignore the alpha channel with or without a soundtrack. For movie exports that require an alpha channel, use the QuickTime "ProRes 4444" presets or the "Animation" or "PNG" codec in the "QuickTime Movie" output format.
•	On Windows, exports using the "MP4 (H.264-AAC)" preset only support output resolutions up to 1080p. If you wish to export to higher resolutions, use the "AVI Movie".
•	On Windows, presets like MP4 (H.264-AAC) require hardware acceleration for the video encoder. If you are noticing issues when exporting or previewing animation, make sure you are using the latest drivers for your video card. If that doesn’t work, try unchecking “Enable export/import hardware acceleration” in the application preferences.
•	Use the transform bones tool to control the movement of the gorilla's eyes in the Characters/Moho 12 folder by clicking and dragging the base dot on the bone
•	On Windows, when Moho is used with a Wacom tablet there are several anomalies with Moho registering inputs from the stylus, primarily around pressure when Windows Ink is enabled.
•	When GPU Acceleration is turned ON several anomalies present themselves in the preview workspace. Including, but not limited to, masking preview errors, and blurriness of switch layers. GPU Acceleration is an experimental feature.
•	Using Moho's bitmap tools on image layers referencing a PSD will lead to unexpected results. When you draw in Moho on a PSD image layer, that information is not passed back to the PSD and the PSD doesn't update. The new PSD importing options "Layers to PNGs" should be used if you wish to use Moho's bitmap tools.



------------------------------------------
Important Information:
------------------------------------------

•	You may need to have Adobe Reader installed to view the included PDF manuals. You can download the latest version of Reader by going to: http://get.adobe.com/reader/
•	It's recomended you turn off Windows Ink if experiencing issues while working with a tablet pen stylus.


------------------------------------------
System Requirements
------------------------------------------

Windows: 

•	Windows ® 10 recommended *
•	64-bit OS required
•	2.0 GHz Intel Core i3 or higher
•	4 GB RAM or higher
•	1.6 GB free hard drive space or higher
•	OpenGL 4.1 supported graphics card required (1920x1080 recommended) **
•	Online connection required to perform online activation


Macintosh: 

•	Macintosh ® OS X 10.13 or 10.14 recommended *
•	64-bit OS required
•	2.0 GHz Intel Core i3 or higher
•	4 GB RAM or higher
•	1.6 GB free hard drive space or higher
•	OpenGL 4.1 supported graphics card required (1920x1080 recommended) **
•	Online connection required to perform online activation


* Smith Micro has done extensive testing of Moho on Windows 10, macOS 10.14, and macOS 10.13. Moho can be installed on older operating systems, but this is not recommended as there might be instabilities. Moho will not work on anything older than Windows 7 (version 6.1) or macOS 10.10.  Smith Micro will only provide full technical support for issues on Windows 10, macOS 10.14, macOS 10.13, and limited support for Windows 7 issues.  

** For high pixel density displays, minimum resolution will vary according to the operating system recommend scaling level. For example, if the OS recommends a scaling level of 200%, the minimum requirement may be as high as 2736x1824 resolution. Or if the OS recommends a scaling level of 150%, the minimum requirement may be as high as 2160x1440 resolution.


------------------------------------------
Technical Support
------------------------------------------

US & GLOBAL SUPPORT:

Please visit our Web site for the latest information on registration and technical support. For up to date information on our technical support policies or for our online frequently asked questions go to: https://support.smithmicro.com 

Note: Smith Micro reserves the right to change its support policies at any time.


------------------------------------------
Content Distribution
------------------------------------------

Please refer to Section 5 ("Content License") of the Moho - End User License Agreement ("EULA") included with this software for more information on modifying and distributing existing Moho content.


------------------------------------------
Copyright & Trademark Notice
------------------------------------------

Smith Micro Software, Anime Studio, Moho, Moho Debut and Moho Pro are trademarks of Smith Micro Software, Inc.  Lost Marble are trademarks of Lost Marble, Inc.  All other product names mentioned in the Software, the Documentation, or other documentation are used for identification purposes only and may be trademarks or registered trademarks of their respective companies. Registered and unregistered trademarks used herein are the exclusive property of their respective owners.  For purposes of Japan law regarding unregistered trademarks (e.g., a pending trademark application), the right in and to a trademark in Japan may not be exclusive until it is validly registered.  You may not remove, modify, alter, cover or deface any trademark, trade names, product names, logo, copyright or other proprietary notices, legends, symbols or labels in the Software and Documentation.  This EULA does not authorize you to use SMSI's or its licensors' names or respective trademarks.  Further, any reference to any third party commercial products, processes or services by trade name, trademark, logo, and company and/or product/service names mentioned or displayed in the Software (and in any of its related Documentation and materials in any form) does not constitute or imply SMSI’s endorsement, recommendation or favoring by SMSI or any of its suppliers/licensors.




Version:  20190625