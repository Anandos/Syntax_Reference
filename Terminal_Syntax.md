//Terminal is a text input, output environment. A wrapper for the shell.<br>
//Shell interprets commands from the user for the kernel and outputs the results sent from the kernel.<br>
//Kernel is the lowest level of the OS that interacts directly with the computer hardware.
|Command|Description|
|-------|-----------|
|cd /path/to/directory	|//absolute path from any present directory|
|cd path/to/directory	|//relative path from present directory|
|pwd	|//present working directory|
|mkdir new_directory	|//create new directory|
|rm filename	|//remove file|
|rmdir directory	|//remove empty directory|
|rm -r directory	 |//delete directory with files inside|
|variable_name=value	|//sets an environment variable in the shell|
|echo $variable_name	|//print to terminal|	
|cp -r -I -I -u -v file.txt backup/	|//copy ‘I’ Interactive all files, ‘I’ interactive prompt before each file, ‘u’ update only copies if destination file is older or missing, ‘v’ verbose, ‘r’ recursive for directories|
|cp -r directory/ directory_backup/ |//copies directory and all contents into specified directory|
|mv file.txt directory/	|//move file to directory|
|touch file.txt	|//create file|
|cat -n -b -e file.txt	|//concatenate command to view, manipulate files. ’n’ numbered lines, ‘b’ number non-empty, ‘E’ visualise line breaks with ‘$’|
|cat file1.txt file2.txt > merged.txt|//concatenates and displays files, then combines and saved them to merges.txt, separated by \n|
|grep “error” file.txt -r -I -n -v -l -c	|//global regular expression print, search for text patterns in files. ‘I’ Ignore binary files, ’n’ number lines, ‘v’ invert match to show text without “error”, ‘l’ only show file names, ‘c’ only show file count|
|find directory/path -name “file.txt” -type f -size  +1M -mtime -7 -user root -delete	|//finds files based on name, type, size or time last modified in days, user permission, empty for empty directories, atime for time last accessed in days|
|find directory/ -type d -empty -atime 1|//searches for empty directories that were accessed between 24-48 hours ago. ‘-type d’ search for directories only, ‘-empty’ empty directories, ‘time 1’ who was accessed 24 hours ago rounded to the nearest day|	
|chmod u+w file.txt u g o a r w x + - =	|//change mode of file permissions, r read, w write, x execute, —- no permissions, rwx full permissions, <br>u user, g group, o others, a all of the above (default), - remove permission, + add permission, = set permission, remove others|
|kill -signal ProcessIDs	|//kill process using a signal command and process IDs. 1 SIGHUP, 2 SIGINT, 5 SIGKILL, 15 SIGTERM,  
|killall firefox	|//killall processes with the name Firefox|
|top -p 1234	|//monitor process resource usage, can be used ‘top’|
|man command	| //manual for command, specifying usage, options, examples|
|sudo apt update | //updates metadata for repositories without installing anything|
|sudo -l -v|//lists user allowed and forbidden commands, -v extends user credentials if valid or asks for password, |
|which brew, which vscode	|//path of an application install|
|history	|//history of previous commands, each command is numbered<br>!n to rerun command number n|
|ps	|//shows current processes; process ID (PID), CPU time, command name|
|command && command \|\| command <br> command; command <br>cat main.cpp \| grep “Cells”| <br>//&& adds commands in chain, both must succeed  <br>\|\| do left command else do right hand command <br>\|feed right hand output into input for left hand command"|
|//Ctrl+C sends SIGINT command to computer||
|brew —version	|	//display current Homebrew version|
|brew install sfml|	//installs this package and it’s dependencies|
|brew list	|	//lists Homebrew packages (formulae and casks)|
|brew uninstall sfml|	//deletes package and it’s dependencies|
|brew cleanup	|	//deletes old versions of packages and old cache files (120 days)|
|brew info sfml	|	//display package version, decencies, installation status, |
|brew update	|	//update Homebrew package index without installing (run before brew upgrade)|
|brew upgrade	|	//upgrades outdates installed packages to the latest version|
|brew search sfml|	//searches for formulae and casks for package|
|brew autoremove|	//removes decencies that are no longer needed|
|'formulae’, ‘casks’|//formulae are command line packages, casks are apps accessible to regular user|
	
