# TextEditor (java) Modifications

This is a simple text editor. Using it as a starting point, it needs a bunch of functionality additions.

## First Things

- Put this code into a Maven project.
- Get it running, it uses the Swing AWT took kit for the graphical UI.
- Now, how would you use a _Dispatch Table_ like pattern the one described here: [Dynamic Dispatch and Dispatch Tables](https://dev.to/philiphaines/dynamic-dispatch-and-dispatch-tables-kdm)
- Move the implmentations of the commands (what happens when you "do" that operation) into separate, different methods.
- Also, create a new class `Main`, which creates the `TextEditor` object and sets it running. (this will require reworking the `TextEditor` constructor)

Now do these additions.

## Additions

Things to add:

- find/replace text implementation
- when you exit, you must NOT lose un-saved changes
- add a new window, scrollable, with some editor help documentation in it.
- implement Word Wrap (yeah, look it up)
- add a font panel, so you can change the font you edit in.
  - make sure not only new files are in the new font, but existing windows too.
- add a way to print the current file.
- add a way to set the page in portrait or landscape mode
- Make your About Dialog snazzy!
