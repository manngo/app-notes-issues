# App Notes

App Notes is a Menu Bar application which gives you the ability to add notes for individual applications. Each Application owns a single note which can be saved indefinitely.

## Bug Reports, Feature Requests and Other Issues

Visit:  [Issues](https://github.com/manngo/app-notes-issues/issues)

## Usage

Once the application is launched, you will see an additional icon in the menu bar. Select it, and a note sheet will popup.

- Add or edit the text
- Save the Note

You can also:

- Revert the Note

	Restore the note to the last saved version
	
-	Delete Note

	Delete the note permanently

There is also a drop-down menu for additional functions.

###	Closing

You can close the note in two ways:

- Click on the Close Button
- Press <kbd>esc</kbd>

You can quit App Notes by selecting Quit from the drop-down menu.

###	Unsaved Notes

When you make any changes, the border will change to remind you that it is no longer the same as the saved note.

If you close and re-open the note, the changes will be remembered. However, if you close and open for a different application, the unsaved changes will be lost.

##	Settings

You can change the appearance of App Notes by selecting <span class="button">Settings…</span> from the dropdown menu:

-	Font

	Note that only monospaced fonts are listed.

-	Auto Save

	This will automatically save the note when the note is closed

-	Window Size

-	Appearance

-	Launch on Login

When you make your changes select <span class="button">OK</span> or <span class="button">Cancel</span> if yo change your mind.

You can reset settings to the default values by selecting <span class="button">Reset Settings</span>

##	Exporting and Importing Data

-	You can export your saved notes to a JSON file by selecting `Export to JSON …`

-	You can import to your saved notes to a JSON file by selecting `Import JSON File …`

	Note that this will delete your previously saved notes.
	
-	If you have already exported your notes, you can export them to the same file using `Export to JSON Again`. If the file doesn’t exist, this will be the same as `Export to JSON …`

##	Common Note

There is one additional note available in any Application. If you hold <span class="button">option</span> while opening App Notes, you will see a shared note page.

This can be used, for example when copying between individual Application Notes, or as a simple scratch pad.

##	Known Issues

The following are know issues, but I would welcome your own experience.

-	Highlighting of MenuButton and Picker

	If you have Accessibility | Display | [<input type="checkbox" checked> Reduce transparency] selected the dropdown menus don’t highlight properly.
	
	I have implemented a partial workaround, so the menus will probably look normal. Still working on the Fonts menu, however.

-	After Select All, you can’t edit text. Sometimes.

	Workaround: If you press an arrow key, you will go to one end or another, and text can be edited normally. No idea why this happens.

-	Sometimes you can’t edit name on Save

-	Dark Mode needs work

	I might disable it till I can fix it.

-	Width doesn’t update immediately after settings change.

	Next time you open the note it’s OK.

-	I can’t get the standard font picker to work, so, for now, you’re stuck with a menu and a text box.

-	Auto Save isn’t implemented.

	I’m not sure that Auto Save is such a good idea anyway. In any case, it gets complicated when combined with the next issue.

-	Close on Unfocus may lose changes

Finally,

-	Launch on Startup hasn’t been fully tested

### To Do

-	Need better highlighting of changed content
-	Update date seems to change too soon
-	Select other applications to view/edit their notes without opening or selecting the application itself
-	About Pane
-	Better Close Button

And, of course, I need proper artwork for the icons.

### Possible Enhancements:

-	Synchronise with iCloud

	Possibly in a future version

Maybe:

-	MarkDown
-	Resizable
-	Individual Settings (nil => global): Font & Size
-	To Do tab

Possible Pro Version:

-	Multiple Notes per Application

