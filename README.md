# evernote-dump

Get all of your attachments out of your exported Evernote enex file and include the correct file dates.

Evernote-dump works by streaming the .enex file through a parser so even extremely large .enex files should work.

# Installation

Before running the Evernote.py script be sure to install.

> pip install filemagic
> pip install html2text

# Instructions

Run using

> python Evernote.py FILE.enex

All attachments found will be output the the "output" folder in the same directory as "Evernote.py"

All the files found in the enex files will be put in the "output" folder

# Road Map

- [x] Export all attachements.
- [x] Keep the modified dates.
- [x] Keep file names if desired.
- [x] ~~Don't depend on fileMagic since it doesn't play nice~~ Now working correctly.
- [x] Make compatible with different versions of filemagic.
- [x] Make multilingual just for fun.
- [ ] Export actual notes.
  - [ ] Add links to the images that were extracted.
- [ ] Convert notes to mark down.
- [ ] Make compatible with QownNotes.
- [ ] Add more error check to combat human errors
- [ ] Get rid of cleanup warning.
