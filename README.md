## Operating-System-Lab
### Exp1: Basics of unix commands
##### PROCEDURE: Login into the ubuntu terminal use Ctrl + Alt + t windows shortcut key or go to activity bar search for terminal and mouse click the terminal open.
### General Commands
```unix
  date
  Used to display the current system date and time.
  date +%D
  Displays date only
  date +%T
  Displays time only
  date +% Y
  Displays the year part of date
  date +% H
  Displays the hour part of time
  cal
  Calendar of the current month
  cal year
  Displays calendar for all months of the specified year
  cal month year
  Displays calendar for the specified month of the year
  who
  Login details of all users such as their IP, Terminal No, User name,
  who am i
  Used to display the login details of the user
  tty
  Used to display the terminal name
  uname
  Displays the Operating System
  unameOperating System Lab Manual Department of CSE, SRIT, ATP
  Prepared by Mr. M. Narasimhulu, 4
  Shows version number of the OS (kernel).
  uname –n
  Displays domain name of the server
  echo "txt"
  Displays the given text on the screen
  echo $HOME
  Displays the user's home directory
  bc
  Basic calculator. Press Ctrl+d to quit
  lpfile
   Allows the user to spool a job along with others in a print queue.
  man cmdname
  Manual for the given command. Press q to exit
  history
  To display the commands used by the user since log on.
  exit
  Exit from a process. If shell is the only process then logs out
```
![date_command](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/4d3bb9de1efcb282d9233a0b0e01e542b2254b4e/date(1).png)
![date_only](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/f58d29a5c74c2bf146302ad9936b6088a5ac3076/date2(1)(1).png)
![time_only](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/07ef489062189dbdacaf9311be0e94c0474df05e/date3(1)(1).png)
![year_only](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/9b8bdcbba80d461824fd9a4a7fea3e22f89d6aa3/date4(1)(1).png)
![hour_only](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/d3bbb3faf66ebca9c4dbfd1806b49117e4f0c436/date5(1)(1).png)
![cal_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/93fb26304bac35b881a1bf372d66c0e2c264f68d/cal.png)
![cal_year1](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/d4a4845b2b83d6f414fe8a20dae390d228c7c542/calyear.png)
![cal_year2](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/176a99bd91b5dcbfab52ec747b51cdb9ff5b05d7/calyear2.png)
![cal_month_year](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/e2d2bb2be981d6463ddae7f48bf6e0e116f868ff/calmonthyear.png)
![who_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/8e3fe5aa385507b7f96b4687e6d89ec699df3035/who.png)
![whoami_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/e16e46c6bd329aa172b7c0207cc8e50372e9ab02/whoami.png)
![tty_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/6365dfdde0f241a44b9e28bffc26dd0e52f92dc8/tty.png)
![uname_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/a72df4285d2c702236e702cb92e5ee47af2423d8/uname.png)
![uname_-r](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/12144fb98927e6c8100c37622ec213a91009dc76/uname%20-r.png)
![uname_-n](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/de144b0b519ee107970cf107262a356e3b914c1a/uname%20-n.png)
![echo_txt](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/58a3f17bbf05378da417e855d907752374eba193/echotext.png)
![echo_$HOME](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/cc5c82aefb148249cb49ebda67df14a209f95428/echo%24Home.png)
![bc_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/12f7cbf8e3ec1fa3af055976b812eeed08d4c04b/bc.png)
![man_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/fe9b16f36fbe03d5dc052ac1283bb145844f39e3/mantty.png)
![man_cmd1](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/451d8cb5237b05db1629117f535034fb5138b874/mantty2.png)
![history_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/dc710fa8c3debeb89e953bf39f69c468ea24f4f9/history.png)
![history1](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/d50460ab6a165a7e7f74289a06b7c9a81c15494e/history1.png)

### Directory Commands
```unix
  pwd
  Path of the present working directory
  mkdir dir
  A directory is created in the given name under the current directory
  mkdir dir1 dir2
  A number of sub-directories can be created under one stroke
  cd subdir
  Change Directory. If the subdir starts with / then path starts from root (absolute)
  otherwise from current working directory.
  Cd
  To switch to the home directory.
  cd /
  To switch to the root directory.
  cd ..
  To move back to the parent directory
  rmdir subdir
   Removes an empty sub-directory.
  ```
   ![pwd_cmd](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/b957959cd6f81c63de6dc96fa681c2716cf19705/pwd.png)
   ![mkdir dir](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/50c1ce22f133b054cd5b87b2d07418b2a399f1bb/mkdir%20dir.png)
   ![mkdir dir1 dir2](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/25ead300f5250bd34fd28d0fb0d7436b631b178a/mkdir%20dir1%20dir2.png)
   ![cd_cmds](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/d218af202e31526ef3306d600d91cd78e52b05f2/cd_all.png)D

   ### File Commands

   ```unix
  cat >filename
  To create a file with some contents.
  To end typing press
  Ctrl+d.
  The >symbol means redirecting output to a file. (<for input)
  cat filename
  Displays the file contents.
  cat >>filename
  Used to append contents to a file
  cp src des
  Copy files to given location. If already exists, it will be overwritten
  cp –i src des
  Warns the user prior to overwriting the destination file
  cp –r src des
  Copies the entire directory, all its sub-directories and files.
  mv old new
  To rename an existing file or directory. –i option can also be used
  mv f1 f2 f3 dir
  To move a group of files to a directory.
  mv –v old new Di
  Display name of each file as it is moved.
  rm file
  Used to delete a file or group of files. –i option can also be used
  rm *
  To delete all the files in the directory.
  rm –r *
  Deletes all files and sub-directories
  rm –f *
  To forcibly remove even write-protected files
  ls
Lists all files and subdirectories (blue colored) in sorted Order
ls name
To check whether a file or directory exists.
ls name *
Short-hand notation to list out filenames of a specific pattern.
ls –a
Lists all files including hidden files (files beginning with .)
ls –x dirname
To have specific listing of a directory.
ls –R
Recursive listing of all files in the subdirectories
ls –l
Long listing showing file access rights (read/write/execute-rwx for user/group/others-
ugo).
cmp file1 file2
Used to compare two files. Displays nothing if files are identical.
Wc file It produces a statistics of lines (l), words(w), and characters(c).
chmod perm file
Changes permission for the specified file. (r=4, w=2, x=1)
chmod 740 file
sets all rights for user, read only for groups and no rights for others
```

   ![filecmd1](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/d943479b267ad11383183551749533a365433392/filecmd1ospic.png)
   ![filecmd2](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/4e7d625d100eb2167c2003ea45a1591c6c4e38bc/filecmd2ospic.png)
   ![filecmd3](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/2caa0b74e90b946a298308b633c6744715054c5c/filecmd3ospic.png)

   ## RESULT
 Thus the study and execution of Unix commands has been completed successfully.

 # Simulate UNIX commands like cp, ls, grep, etc
> ## Cp simulate command Source code
```c
#include <stdio.h>
#include <stdlib.h>
void simulate_cp(const char *source, const char *destination) {
FILE *src = fopen(source, "r");
FILE *dest = fopen(destination, "w");
if (!src || !dest) {
perror(!src ? "Error opening source file" : "Error opening destination file");
if (src) fclose(src);
return;
}
char buffer[1024];
size_t bytes;
while ((bytes = fread(buffer, 1, sizeof(buffer), src)) > 0) {
fwrite(buffer, 1, bytes, dest);
}
printf("File '%s' copied to '%s'\n", source, destination);
fclose(src);
fclose(dest);
}
int main(int argc, char *argv[]) {
if (argc != 3) {
fprintf(stderr, "Usage: %s <source_file> <destination_file>\n", argv[0]);
return EXIT_FAILURE;
}
simulate_cp(argv[1], argv[2]);
return EXIT_SUCCESS;
}
```
![cp1](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/6a2157f47494f235707f2ec74ff6e7763a2e622c/1bcp1.png)
![cp2](https://github.com/BhavaniJagirdar/Operating-System-Lab/blob/5d8b33afcef624a7c5e2c4c9a5658f391707f5fa/1bcp2.png)

## Simulation code for ls command
```c
#include <stdio.h>
#include <stdlib.h>
#include <dirent.h>
void simulate_ls(const char *path) {
struct dirent *entry;
DIR *dir = opendir(path);
if (!dir) {
perror("Error opening directory");
return;
}
while ((entry = readdir(dir)) != NULL) {
if (entry->d_name[0] != '.') {
printf("%s ", entry->d_name);
}
}
printf("\n");
closedir(dir);
}int main(int argc, char *argv[]) {
const char *path = argc > 1 ? argv[1] : ".";
simulate_ls(path);
return 0;
}
```



