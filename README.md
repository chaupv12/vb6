# vb6

1) need back up VBA6.DLL file to recover: D:\working\setup\Visual_Studio_6.0_Enterprise_English_CD_Edition\dsk1\VB98 to C:\Program Files (x86)\Microsoft Visual Studio\VB98 in case it demages

2) use VBEThemeColorEditor: D:\working\VB6_MouseWheel\VBEThemeColorEditor

3) HxD: for Hexa editor: https://mh-nexus.de/en/downloads.php?product=HxD20


4)  Navigate in regedit to HKEY_CURRENT_USER\Software\Microsoft\VBA\6.0\Common\CodeBackColors

   * change value to : 2 7 1 13 15 2 2 2 11 9 0 0 0 0 0 0 

5)  change CodeForeColors to : 13 5 12 1 6 15 8 5 1 1 0 0 0 0 0 0 

6) change FontFace to : Consolas

7) use VBEThemeColorEditor.exe to load VS2012 Dark.xml


8) Refer:
D:\working\VB6_MouseWheel\VBECustomColors-master\README.md



B) VB6 Shortcut key


View definition 		SHIFT+F2
Go to last position 	CTRL+SHIFT+F2

View Code window 		F7
View Object				SHIFT + F7

View Object Browser 	F2
Find 					CTRL+F
Replace 				CTRL+H
Find Next 				SHIFT+F4
Find Previous 			SHIFT+F3
Next procedure 			CTRL+DOWN ARROW
Previous procedure 		CTRL+UP ARROW
View definition 		SHIFT+F2
Shift one screen down 	CTRL+PAGE DOWN
Shift one screen up 	CTRL+PAGE UP
Go to last position 	CTRL+SHIFT+F2
Beginning of module 	CTRL+HOME
End of module 			CTRL+END

Move one word to right 	CTRL+RIGHT ARROW
Move one word to left 	CTRL+LEFT ARROW
Move to end of line 	END
Move to beginning line 	HOME
Undo 					CTRL+Z
Delete current line 	CTRL+Y
Delete to end of word 	CTRL+DELETE
Indent 					TAB
Outdent 				SHIFT+TAB
Clear all breakpoints 	CTRL+SHIFT+F9
View shortcut menu 		SHIFT+F10


MORE: refer to https://www.johnsmiley.com/cis18/smiley024.pdf





C) Refer: https://www.davidtan.org/vb5-vb6-keyboard-shortcuts-reference-list/

VB5 & VB6 Keyboard Shortcuts Reference List
Here is a list of shortcut key combinations that can be using while developing applications in VB5 or VB6


IDE Navigation

F2 Object Browser
F4 Property Window
Shift+F4 Property Pages
F6 Change Window (Split Window Mode)
F7 Code Window
Shift+F7 Object (Design) Window
Ctrl+D Add File
Ctrl+E Menu Editor
Ctrl+G Immediate Window
Ctrl+L Call Stack (When in RUN mode)
Ctrl+R Solutions Explorer
Ctrl+T Component Window
Ctrl+PgUp Go to Previous Sub/Function/Property (Declaration Line)
Ctrl+PgDn Go to Next Sub/Function/Property (Declaration Line)
Ctrl+Up Go to Previous Sub/Function/Property (First Line after Declaration)
Ctrl+Dn Go to Next Sub/Function/Property (First Line after Declaration)

Code Navigation

Shift+F2 Definition
Ctrl+Shift+F2 Last Cursor Position
F3 Find Next (Last searched item)
Shift+F3 Find Previous (Last searched item)
Ctrl+F3 Find Next (Current Selection)
Ctrl+Shift+F3 Find Previous (Current Selection)
Shift+F10 Context Menu (occasional erratic behaviour, use ContextMenuKey instead)

Form Designer

Shift+Arrow Resize Control
Ctrl+Arrow Move Control (Direction)

Code Edit Shortcuts

Ctrl+Space Complete Word
Ctrl+J List Properties/Methods
Ctrl+Shift+J List Constants
Ctrl+I Quick Info
Ctrl+Shift+I Parameter Info

Run

F5 Start/Continue
Ctrl+F5 Start with Full Compile
Ctrl+Break Break
Shift+F5 Restart

Debug

F8 Step Into
Shift+F8 Step Over
Ctrl+Shift+F8 Step Out
Ctrl+F8 Run To Cursor
Ctrl+W Edit Watch
Shift+F9 Quick Watch
F9 Add/Remove Breakpoint
Ctrl+Shift+F9 Clear All Breakpoints
Ctrl+F9 Set Next Statement
Ctrl+RightArrow Show End Variable Value (tooltip displying variable value is truncated, use left arrow to view start again)
