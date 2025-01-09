Guidelines

The purpose of this repository is to provide guidance on how I like to work,
mostly regarding software but may include other things.

This is intended to be a set of guidelines only. Deviating from this is allowed
and probably necessary in some cases. This is here to answer the question "How
do I normally do this?".

For guidelines on how to write files for this set of guidelines, see the file
named "meta".


Readme

This file also serves as the guidelines for how to write a readme.

Perhaps these guidelines apply to more that just readme files and should be
abstracted.

Format
- plain text.
- Easy to read in a terminal emulator.
- Markdown is nice for Github but I value reading in the terminal.

File Extension
- Use ".txt". It's a plain text file.
- Let the editor configure itself with indentation rules for the user.

Line Wrap
- Wrap at 80 characters
- This is another optimisation for terminal.
- Automatic wrapping is not great in bash or the terminals that I've used. It
  can cause text to be erased when you make the window narrower than the line.
- Automatic wrapping in very wide windows creates very long lines. This can make
  it a little annoying to find the next line when you readto the end of a line.
- Do not wrap within words unless the word is longer then the entire line, in
  which case, maintain indentation and read as though the indentation is not
  part of the word.

Indentation
- Indent with two spaces.
- I prefer tabs in almost all other contexts but to enforce an 80 character
  manual wrap, you can't indent with tab characters which are often anywhere
  between 2 and 8 charachters long.

Layout
- The first line should be the title of the file which is likely the same as
  the filename.
- Typically the title should be followed by a brief description or summary of
  the file which justifies it's existance.
- Avoid the hierarchial indentation that works so well but creates a lot of
  text density. This can be a little hard to navigate; it creates a solid lump
  of text with little shape. Hard to scan.

Sections
- Consists of: double newline, title, newline, then the content of the section.
- The doulble newline seperates it from the title or preceeding section.
- A section may consist of multiple subsections but not just one
  subsection.
- A section may have multiple forms of content, including text, lists and
  subsections.
- Subsections should generally be the last content in a section.

Subsections
- Consists of: a single newline, title then the content of the section.
- Subsections must not have subsubsections. If more depth is required, break the
  file into multiple files.
- More depth in one file looks messy and can be a little more unpleasant to
  read.

Title
- Capitalise with title case (wow!).
- Should not be indented.

Text Content
- Should be indented one level more than the title. This puts text at the same effective indentation as lists and is pleasing to scan with the eyes.

Lists
- Lists should either be bullet points, numbered lists or key-value pairs.

Bullet Points
- Use a dash as the bullet.
- Leave one space between the bullet and content.
- Wrapped lines in a bullet point should be indented to the same level as the
  start of the text at the beginning of the bullet content.

Numbered Lists
1. One number, one full stop then one space.
20. Do not attempt to vertically align the content of the list item. It's not
    worth the time it would take to adjust all the lines if you reach the 10th
    or 100th item.
300. This subsection is an example that demonstraits the unfortunate but
     acceptable vertical mislignment caused by numbers of different character
     count.

Key Value Lists
- Constists of the key, one colon, one space and the value of the content
- If the value is long enough to wrap, indent it to the same level as the start
  of the value content.
- If a "too many" values in a key-value list are along enough to wrap, consider
  a different approach, maybe use subsections or break the document up into
  multiple files.

