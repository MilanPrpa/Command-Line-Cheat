# git.cheat
## Some Basic Git commands:
```
pwd: shows what directory you are currently in.
ls, ls-l, ls-la, ls-lah: list the contents of present working directory.
cd: change directory
touch: used to create file.
echo $0: shows what shell you are using.
echo $SHELL; type shell name to move into it.

nano: text editor; there is also emac and vim; 
  ctrl-x to save changes.
cat: read files; also concatenates files.
more:
less: shows less of the file instead of the entire file.
man: manual on different commands.
head: display lines from beginning of file
tail: display lines from end of file.
mkdir: make a directory.
mv: move file. mv <file> <path>; also, can rename file.
  -n: no overwriting
  -f: force overwriting
  -i: interactive overwriting
  -v: verbose
cp: copy. cp <file> <newfilename>
  -n: no overwriting
  -f: force overwriting
  -i: interactive overwriting
  -v: verbose
rm: only removes file, completely.
rmdir: remove directory. Only remove directories that are empty.
rm -R: remove non empty directories. Really powerful.
Search Files & Directories:
  (find path expression)===> find ~/Desktop <name>
whoami: indicates who the user is.
chown milan:staff <file name>::
Permissions = read... User Group Other
              write
              execute
chmod: change mode.
sudo = substitute user and do.
***Command Basics***
/bin/: store files.
whereis <name of what you are looking for>: tells you where you can find programs.
whatis: explains what program does.
-v, --version, --help: can tell you what version or give extra help.
EXIT: q, x, ctrl + q,x
FORCE QUIT: ctrl + c
$PATH
***System Info Commands***
date:
uptime:
users:
uname: operating system name. MAC unix version is Darwin.
uname -mnrsvp:
*** Disk Information ***
df:
df -h: the -h means humanize.
du: 
** Viewing Processes **
ps u: shows user
ps aux: more info.
top: monitoring processt
ctrl + n: new terminal
kill <process id# >: kill process; kill -9 <process id# >: the -9 forces the kill.






