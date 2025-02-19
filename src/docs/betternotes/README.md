---
description: "The bot built for one job: to make note taking and sharing even more powerful"
---

# BetterNotes
The bot built for one job: to make note taking and sharing even more powerful

## Features
Create, edit, and share notes with anyone on discord

## Documentation
prefix: **`n`**
To create multiple work note titles, use `""`

**`nnew [title] [content]`**: 
> Creates a new note with [title] and [content]
> ex: `nnew "my note" This note title has 2 words!`
> ex: `nnew note1 This is note title has only 1`

**`nread [title]`**
> Opens the note with [title]

**`ndelete [title]`**
> Deletes the note with [title]
> Only the note owner can do this

**`nedit [title]`**
> Provides the edit menu to edit a note
> 3 options:
> - editing: Add new content
> - replacing: Replace lines or words
> - removing: Remove lines or words 

**`nlist`**
> List all the notes you have access to

**`nshare [title] [@user1 @user2 ...]`**
> Shares the note with [title] to all users mentioned
> Notes which are shared can be edited by all
> Only the note owner can do this

**`nremove [title] [@user1 @user2 ...]`**
> Removes access of note with [title] to all users mentioned
> Only the note owner can do this

**`ninfo [title]`**
> Displays information about a note
> The owner, who it is shared to, and the time of last edit
> Only the note owner can do this

**`nhelp`**
> Displays helpful information (basically this)

## Something is not working!
### I want to use this privately
Use the commands in the direct message channel with the bot. All commands are still supported.
### My notes are not showing
If you set your notes to too many characters, discord will not be able to show an embed with that many.
Try to limit large blocks of text (>2000 characters) to multiple notes.
### For some reason the bot is not working
If the bot is not working, try reinviting it with [this link](https://discord.com/api/oauth2/authorize?client_id=855324401373544458&permissions=519232&scope=bot)
### I want to save a file
Saving files currently is not supported. There are no plans for this as you can just as easily save a note with the file's url.
### Syntax
Because this is an embed, all normal discord markdown is supported. [read more](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-)
`[text](link)` can be used to apply the link to the text.
### [Support server](https://thymedev.github.io/discord)
