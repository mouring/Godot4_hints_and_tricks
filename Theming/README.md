# Theming

## Discussion

Godot theming is element based. This means you can't tag elements and generate a single style sheet like you do in CSS, but you create a style per element type (Button, Label, etc) and then you use Theme or Theme_Overrides per element you wish to be different than the 

The best design pattern is thus to create a "Master Theme" that should define what your basic look and feel and then define "Sub Themes" to handle things like special case titles, subtitles, etc.

In this directory you'll find all the classes that can be themed within Godot and what theming classes are associated with them.As some have more than one associated with them. As well as there is a simple scene that contains only the elements required for the theming that class.

## Classes

* AcceptDialog
	* Button
* Button
* CheckBox
	* Button
* CheckButton (Aka Checkbox Slider)
	* Button
* CodeEdit
* ColorPick
* ColorPicker
* ColorPickerButton
	* Button
* ColorPresetButton
* Dialogs
* FileDialog
	* AcceptDialog
	* Window 
* Fonts
* GraphEdit
* GraphEditMinimap
* GraphNote
* GridContainer
* HBoxContainer
* HFlowContainer
* HScrollBar
* HSeparator
* HSlider
* HSplitContainer
* HeaderLarge
* HeaderMedium
* HeaderSmall
* Icons
* ItemList
* Label
* LineEdit
* LinkButton
* MarginContainer
* MenuButton
* [OptionButton](OptionButton/) (aka DropDown)
 	* Button
 	* PopupMenu
* Panel
* PanelContainer
* PopupDialog
* PopupMenu
* PopupPanel
* ProgressBar
* RichTextLabel
* ScrollContainer
* SpinBox
* TabBar
* TabContainer
* TextEdit
* TooltipLabel
* TooltipPanel
* Tree
* VBoxContainer
* VFlowContainer
* VScrollBar
* VSlider
* VSplitContainer
* Window
