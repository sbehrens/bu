#bu
================================

Utility for quickly backing up files and directories.  Copy 'bu' your path and set to execute. 

bu creates a directory named BACKUP in the folder the files and/or folders you are backing up.  bu bzip's these files with a timestamp.

##Options
--------------------------------

```
usage: bu [options] filename (dirname)

file and diretory backup utility

optional arguments:
  -h, --help            show this help message and exit
  -f files [files ...]  filename(s) or directory(s) to backup
  -D backupdir          backup dir name (default BACKUP)
```
Backupdir will be created in the current directory you are in.  

##Examples
--------------------------------
**Backup a file named foo**

``` [user@hostname opt]$ bu -f foo ```


**Backup directory named bar**

``` [user@hostname opt]$ bu -f bar/ ```


**Backup a file named foo and a dir named bar to the backup location audit**

``` [user@hostname opt]$ bu -f foo bar/ -D audit ```


