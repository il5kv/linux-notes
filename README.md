# linux-notes


| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

RHCSA RHEL

| Command | Description |
| --- | --- |
| man command	|
| -h	|
| --help	|
| -?	|
| Files, Directories	
| pwd | current dir|
| $HOME	|
| cd ..	|moves one dir up
| cd-	|moves to previous dir
| cd ~username	|goes to home dir
| cd	|goes go your home dir
cp file.txt tonewfile.txt	
| cp -R /home/dir /home/newdir	copies directories with -R
| mv old_name new_name	renames files; also moves with mv /dir
| mkdir -m777 -p /dir1/newdir/dir2	m sets perm. 777 is rwx
| 4	-p makes newdir betw. dir1 and dir2
| 2	r
| 1	w
| 764	e
| 	users, group, others
| chmod 764 file.txt	users rwx, group rw, others r
| chown [option] owner[:group] file(s)	
| chwon user file.txt	
| 	makes user owner of file.txt
| rmdir	rm
| touch	make empty file
| cat > fileName
| file file.txt	get type of file.txt
| VIM	
| gg	Beginning of file
| ALT /	end of file
| u	undo last change. capital u undo all changes
| gzip, tar compression	
| gzip fileName	with gzip compression
| gunzip fileName.gz	
| tar -cvf dir.tar /dir	uncompressed tar archive
| tar -cfz dir.tar /dir	gzip tar rachive compression
| -uvf	archives and adds to an existing archive
| -rvf	-||-
| -tvf	lists the contents of a file
| tar -xf file.tar	extract
| tar -xvg file.tar -C /dir	extart at a directory with -C
| Lists	
| df -mh	disk usage in mbs
| du -sh	currect dir usage
| head file.txt	show first 10 lines
| tail -100 file.txt	show last 100 lines (10 by def)
| wc file.txt	counts words/lines
| Find	
| locate -i two*words	search -i (not case sens.) * is empty spc
| find /where -name name.txt	
| find ./ -type d -name dirname	
| 	searches for directories
| grep what file.txt	
| nd /dir -name x	list items beginning with x
| nd /dir -size +100M
| users, ,groups	
| id	show active user details
| who	logged users
| finger	info on all logged users
| finger username	
| pinky	
| w	logged users and activity
| whoami
| last	last logins
| cat /etc/passwd	list users, rights
| cat /etc/passwd | cut -d : -f 1	only usenames
| cat /etc/groups	list groups
| adduser username	
| userdel username
| passwd username	change pw
| usermod -a -G groupname username	
| system	
| ssh user@host	
| ping hostname	
| hostname -i	hostname ip
| uname -a; uptime	sys info
| last reboot	
| ip addr show	
| var, commands	
| let variable=value	integer val.
| set	lists variables and functions
| echo $variable	display value
| env	display all variables
| unset varName	removes a var
| alias name=command	
| unalias name
| watch -n interval command	run through an interval
| watch -n 5 'ntpq -p'	execute and display every 5 secs.
| sleep interval && command	postpone cmnd execution
| where is command	find binary/source/ manual for command
| UTIL	
| logrotate	
| free -mh	
| ps -ef	
| ps -u username	all processes associated with the user
| top	
| htop	improved top
| pidof processName	get the process ID
| kill PID	
| RHCSA	
| >	Writes to a file (and replace all in it)
| >>	Adds at the end of the file
| ~	Root home dir
| ls -al ~ > list	Saves ls to list at home dir
| sort < list	Get input from list and sort it
| -S	by size
| -t	last modified
| ls -smth 2> file 2>&1	 saves errors in a file AND displays them (stderr to sdtout)
	
	
	
	
	
	
	
	
