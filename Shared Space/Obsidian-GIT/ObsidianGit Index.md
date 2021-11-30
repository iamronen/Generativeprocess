# Obsidian/GitHub Index

## Patterns 
These are a collection of patterns & practices that have emerged (from working on both the Digital Space and Wholocracy projects) for creating generative projects with the Obsidian/GitHub environment.
1. [[GenSeq - ObsidianGit New Project]]
2. [[GenSeq - ObsidianGit File Structure]]
3. [[GenSeq - ObsidianGit File Formatting]]
4. [[GenSeq - ObsidianGit Multiple Sequence]]

## Custom Vault CSS
If you have applied the above mentioned patterns then you can install a CSS file that will clean up and organize the view-mode of generative sequences files. For this you need to:
1. Open a file browser.
2. Go to your local folder for the Generative Process vault.
3. Make sure you can view hidden files and folders.
4. Move into the hidden ".obsidian" folder.
5. In it create a folder called "snippets".
6. In that folder create a file "obsidian.css".
7. Copy into that file the contents from [[Custom CSS for Generative Sequences in Obsidian]].
8. Save the file.
9. Restart Obsidian (not sure if this is necessary).
10. Goto Obsidian Settings -> Appearance.
11. Under CSS Snippets you should see the newly added file - enable it.
12. You may need to restart Obsidian again (not sure if this is necessary).
13. Now when you view GenSeq notes they should appear clean and readable without excess/repeating filenames.

## How to Author

These are technical details about how to arrange generative sequences within Obsidian/GitHub. They do not address how to author generative sequences. On that front I can offer these initial suggestions: 
1. Start a new sequence as a numbered list within one note in the sequences folder (see [[GenSeq - ObsidianGit File Structure]]).
2. Start each list item with a tentative title (which will become the title of the transformation) followed by a description of the transformation.
3. Use this single file format to flesh out your initial thoughts, until you have an initial whole-feeling sequence.
4. Only then convert each of the transformations into separate files:
	1. Select the entire text of each transformation (title + description).
	2. Right click -> Extract Current Selection
	3. Press Ctrl  + Enter to create a new note.
	4. Copy the title note into the filename (minus disallowed characters).
	5. Convert the title within the note into a level 5 heading.
	6. Move the card from the root folder (this seems to be where new cards are created) into its proper transformations folder.


