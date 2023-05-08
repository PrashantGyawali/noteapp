# Noter
A simple terminal note app i made to learn file system and node js

**How to run?** 
- run `node noter`

 ### **Commands:** 
* **create**: Creates a new note
    - Syntax: ``create [notename] [text]``
* **append**: Adds to an existing note
    - Syntax: ``append [notename] [text]``
* **delete**: Deletes a note
    - Syntax: ``delete [notename]``,
* **overwrite**: Overwrites an existing note
    - Syntax: ``create [notename] [text
* **read**: Reads a note
    - Syntax: ``read [notename]``
* **rename**: Renames an existing file to newone
    - Syntax: ``rename [notename] [newfilename]``
* **alias**: Lists aliases of command and all aliases if no command name specified 
    - Syntax: `` alias [commandname]``
* **create-alias**: Creates an alias to a command
    - Syntax: `` create-alias [basecommandname] [alias]``
* **delete-alias**: Deletes an alias to a command
    - Syntax: `` selete-alias [basecommandname] [alias]``
* **edit**: Reads a file and allows overwrite
    - Syntax: `` edit [notename]``
* **list**: Lists all the notes
    - Syntax: `` ls`` or   ``list``

## Todo:
- list all notes :heavy_check_mark:
- delete all command :heavy_check_mark:
- command alias :heavy_check_mark:
- edit command ( read + overwrite)  :heavy_check_mark:
- colorizel the commands :heavy_check_mark: