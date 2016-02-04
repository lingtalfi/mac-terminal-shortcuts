Mac terminal shortcuts
===========================
2015-09-23



This will make your Mac Os X terminal have cool and intuitive editing shortcuts:



- ALT-left: move one word backward
- ALT-right: move one word forward
- ALT-backspace: kill one word backward
- ALT-del: kill one word forward
- ALT-up: set word after cursor to uppercase
- ALT-down: set word after cursor to lowercase
- home: move to the beginning of the line
- end: move to the end of the line
- CTRL-backspace: Same as ALT-backspace
- CTRL-del: Same as ALT-del

(Now those are used for tmux resizing)
- CTRL-up: resize pane to the up
- CTRL-right: resize pane to the right
- CTRL-down: resize pane to the down
- CTRL-left: resize pane to the left



How to use
--------------


Simply import the Ling.terminal profile into your terminal.


If you don't know how to do, here are the steps:

- Download the Ling.terminal file.
- Open the terminal, go to Preferences > Profile.
- At the bottom of the left columns (with all the profile), click on the configuration icon and click Import.
- This will open a dialog, choose the Ling.terminal file.
- Now it should appear on the left column.
- Rename it (double click on the textual part "Ling").
- To make it your default profile click the button on the bottom, next to configuration icon (at the bottom of the profiles column).
- Now go to the General tab and set your new profile for opening with new window



Technical notes
--------------------

Those shortcuts are based on the assumption that you are using the emacs command line editing mode,
which is the default on Mac Os X, and in bash in general.

If you are using the set -o vim option, those shortcuts should not work (not tested).





