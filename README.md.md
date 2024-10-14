---
#### 1.Kernel and shell
---
1. Kernel
- Kernel is core of operating system.
- Kernel can access to hardware directly.

2. Shell
- shell is interface that helps communicate between Kernel and user. 
- shell provide a text-based command interface.

---
---
#### 2.CLI(command line interface) vs GUI(graphical user interface)
---

| --- | CLI | GUI |
| --- | --- | --- |
| use | have to remember commands | easy to use and intuitive |
| tool | keyboards, mostly | mouse,some keyboard |
| speed | relatively fast | relatively slow |
| user | developers | daily user |

---
---
#### 3.Shell command
---
1. pwd(print working directory)
- show the current path

2. cd(change directory)
- change directory
- "cd .\. " is moving to upper directory.
- "cd . " is moving to now directory.
- "cd"or"cd ~" is moving to now directory.

3. ls(list)
- list files and directories
- "ls -1"or"ls -l" is to show more information of file.
- "ls -a"or"ls -la" is to show all file including hidden file.

4. path sign
- . : now directory
- .\. : upper directory
- ~ : home directory
- / : root directory

---
---
#### 4.Manipulation
---
1. cp
- "cp file1 file2" copies the contents of file1 into file2
    if file2 doesn't exist -> create file2
    if file2 exist -> file2 is overwritten with the file1
- "cp -i file1 file2" is same to above, but inform overwriting(yes or no) to user
- "cp file1 dir1" copies file1 and paste to dir1(directory)
- "cp -R dir1 dir2" copies the dir1 and
   if dir2 doesn't exist -> create dir2(same as dir1)
   if dir2 exist -> create dir1 in dir2

2. mv
- "mv file1 file2" renames file1 to file2
   if file2 exist -> file2's contents is replaced with file1
- "mv -i file1 file2" is same to above, but inform overwriting(yes or no) to user
- "mv file1 file2 dir1" is that file1 and file2 are moved to dir1
   if dir1 doesn't exist -> mv will exit with an error
- "mv dir1 dir2" renames dir1 to dir2
   if dir2 exist -> dir1 is moved within dir2

3. rm
- "rm file1 file2" deletes file2 and file2
- "rm -i file1 file2" is same to above, but inform deleting(yes or no) to user
- "rm -r dir1 dir2 " deletes dir1 and dir2 including all of their contents

4. mkdir
- "mkdir" make a new directory

5. Wildcards
- "*" means all filenames
- "g*" means all filenames that begin with the character "g"
- "b*.txt" means all filenames that begin with the character "b" and end with .txt
- "data???" means all filenames that begin with the character "data" followed by 3 more characters