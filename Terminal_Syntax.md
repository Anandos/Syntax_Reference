|Command|Description|
|-------|-----------|
|cd /path/to/directory	|//absolute path from any present directory|
|cd path/to/directory	|//relative path from present directory|
|pwd	|//present working directory|
|mkdir new_directory	| |
|rm filename	| |
|rmdir directory	| |
|rm -r directory	 |//delete directory with files inside|
|variable_name=value	| |
|echo $variable_name	|//print to terminal|	
|cp -r -I -I -u -v file.txt backup/	|//copy ‘I’ Interactive all files, ‘I’ interactive prompt before each file, ‘u’ update only copies if destination file is older or missing, ‘v’ verbose, ‘r’ recursive for directories|
|cp -r directory/ directory_backup/	|
|mv file.txt directory/	|
|touch file.txt	|//create file|
|cat -n -b -e file.txt	|//concatenate command to view, manipulate files. ’n’ numbered lines, ‘b’ number non-empty, ‘E’ visualise line breaks with ‘$’|
|cat file1.txt file2.txt > merged.txt	| |
|grep “error” file.txt -r -I -n -v -l -c	|//global regular expression print, search for text patterns in files. ‘I’ Ignore binary files, ’n’ number lines, ‘v’ invert match to show text without “error”, ‘l’ only show file names, ‘c’ only show file count|
|find directory/path -name “file.txt” -type f -size  +1M -mtime -7 -user root -delete	//finds files based on name, type, size or time last modified in days, user permission, empty for empty directories, atime for time last accessed in days
|find directory/ -type d -empty -atime 1	
|chmod u+w file.txt u g o a r w x + - =	"//change mode of file permissions, r read, w write, x execute, —- no permissions, rwx full permissions,
|u user, g group, o others, a all of the above (default), - remove permission, + add permission, = set permission, remove others"
|kill -signal ProcessIDs	//kill process using a signal command and process IDs. 1 SIGHUP, 2 SIGINT, 5 SIGKILL, 15 SIGTERM,  
|killall firefox	//killall processes with the name Firefox
|top -p 1234	//monitor process resource usage, can be used ‘top’
|man command	
|sudo apt update	
|sudo -l -v command argument	
|which brew, which vscode	//path of an application install
|history	
|ps	
|"command && command || command command; command
|Cat main.cpp \| grep “Cells”| |
|"	"//&& adds commands in chain, both must succeed || do left command else do right hand command |
| feed right hand output into input for left hand command"|
|//Ctrl+C sends SIGINT command to computer	|
|//Terminal is a text input, output environment. A wrapper for the shell.	|
|//Shell interprets commands from the user for the kernel and outputs the results sent from the kernel| 	
|//Kernel is the lowest level of the OS that interacts directly with the computer hardware	|	
|brew —version	|	|
|brew install sfml|	|
|brew list	|	|
|brew uninstall sfml|	|
|brew cleanup	|	|
|brew info sfml	|	|
|brew update	|	|
|brew upgrade	|	|
|brew search sfml|	|
|brew autoremove|	|

	
