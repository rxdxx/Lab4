# Shell command:

- **pwd**: shows the current path in a hierarchical directory
- **cd**: change directory 
- **ls**: list files and directories
- ***arguments***: 
  - / : root
  - . : current directory
  - .. : upper-level directory
  - ~ : home of current user
  - /(directory name) : absolute path
  - ./(directory name) : relative path
  - ../(directory name) : relative path


- ***options***:
  - -l : show detailed information (long format)
  - -lh : smae as above, but size in units
 
### More on ls
The ls command is used to list the contents of a directory. It is probably the most commonly used Linux command. It can be used in a number of different ways. Here are some examples:
|**Command**|**Result**|
|:-----|:-----|
|ls|List the files in the working directory|
|ls /bin|List the files in the /bin directory (or ant other directory we care to specify)|
|ls -l|List the files in the working directory in long format|
|ls -l /etc /bin|List the files in the */bin* directory and the */etc* directory in long format|
|ls -la ..|List all files (even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format|

---

### TIP
- Tab key : Autocompletion
- up arrow key : Past commands
- clear : Terminal Screen Reset

---

- **cp**: Copy files and directories
- **mv**: move files and directories or rename them
- **rm**: delete files and directories ***permantely and irreversevely!!!***
- **mkdir**: make a new directory

---

### Manipulation: Wildcards
|**Pattern**|**Matches**|
|:-----|:-----|
|*|All filenames|
|g*|All filenames that begin with the character "g"|
|b*.txt|All filenames that begin with the character "b" and end with the characters ".txt"|
|Data???|Any filename that begines with the characters "Data" followed by exactly 3 more characters|
