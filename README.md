# CLI - Command Line Interface

This is a short cheatsheet to have a basic use of CLI.

- `pwd` (print work directory): It tells you in which directory are you currently located.

```bash
$ pwd
/c/Users/user1/OneDrive/desktop

```

- `whoami` shows the actual username.

```bash
$ whoami
user1
```

- `help` you can make it more especific in certains situations, i.e: `pwd --help`.
  - `\-h` = help.
  - `\--help` = help.
- `clear` cleans the terminal.
- `ls` shows all the content in the especified directory.
- `~` represents the _home_ directory.
- `/` represents the _root_ directory.
- `.` represents the _actual_ directory.
- `..` represents the _father_ directory, with it you can go back by one 'level'.
- `-` represents the _previous_ directory, with it you can go back to the previous directory.
- `""` Folders or files whose name has whitespaces, need to be named between quotation marks.
- `cd` (change directory) enters a directory or switch from one to another.

```bash
$ cd /c/users/user1/desktop
```

Going back to a previousdirectory:

```bash
$ cd /c/users/user1/desktop ..
 -->
$ cd /c/users/user1
```

- `touch` creates files, such as: _README.md, index.html, styles.css, index.js_, etc.

```bash
$ touch README.md
```

- `echo` creates files with actual content, i.e:

```bash
$ echo "# This is a heading" > README.md
```

- `cat` allows to see/visualize the content of a file.
- `mkdir` creater a new directory.
- `rm` removes a file.
- `rmdir` remove/delete an empty directory.

```bash
$ mkdir "new directory"
```

- `rm -r` remove/delete a directory and its contents.
- `rm -rf` forces a directory and its content to be removed.
- `mv` moves files or folders.
- `cp` copy files.
- `cp -r` copy folders and its contents.
- `find` search files or folders.
- `ps` search active system process.
- `kill` remove/delete an active system process. -`vim` opens _VIM_ editor.
- `nano` opens _Nano_ editor.
- `code` opens _VS code_ editor.

```bash
$ code . (Allows to open current directory with VSCode)
```

- `alias` creates a shorcut for a long command.
- `unalias` remove/delete an command alias.
