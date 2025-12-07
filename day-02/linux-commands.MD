# Linux Commands

### File Management

**Command Syntax in Linux**

**`Command <options> <input>`**

> _**Options**_ and _**Input**_ are not mandatory for all Linux Commands.

*you can use multiple options at a time as well*

To list all the files and directories

**`ls`**

Options in the _**ls**_ command

`ls -a` > To view all files including hidden files.

`ls -l` > To view the files and directories along with all information.

`ls -t` > To view the files in the lastest updated time on the top.

`ls -r` > To view the files in reverse alphabetical order.

`ls -ltr` > To view the files along with details and last updated files on the top.

To check the current path

`pwd `

To change the Directory

`cd <path>`

To create a new directory

`mkdir <dir-name>`

Options in **_mkdir_** command

`mkdir -p </dir/dir/dir-name>` > To create nested directories.

To create a empty file

`touch <file-name>`

To view the file content

`cat <file-name>`

Options in **_cat_** command

`cat > <file-name>`

 The Cursor will wait when you enter this command type the content you want to insert in the file and press enter and ctrl+d the content you entered will be stored in the file.
> If there is any content in the file previously that will be overwritten with new content

`cat >> <file-name>`

 The Cursor will wait when you enter this command type the content you want to insert in the file and press enter and ctrl+d the content you entered will be stored in the file.
> new content is appended to any existing content in the file.

To delete file

`rm <file-name>`

Options in *__rm__* command

`rm -f <file-name>` > To remove the file forcefully.

`rm -rf <dir-name>` > To remove the directory recursively

`rm -rf *` > To remove all files and directories in the current directory.

