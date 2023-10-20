# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls


 <img width="389" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/07f015c5-abcb-4d8c-9582-5a1be259dbee">



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


<img width="374" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/a166f7b0-578f-4e5d-aa1f-bd58093719c4">

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


<img width="379" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/fe38ea4d-0406-4323-b70b-894e23df8074">


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


<img width="371" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/d22b2057-6e73-4179-a97a-3ab6c604b023">


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


<img width="372" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/77688a53-85d4-4f36-b898-8bb296c9ffc1">


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


<img width="381" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/aeb8bc7b-cfea-472c-934d-dc80acf34b4f">

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


<img width="384" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/4a50b674-55d6-4efb-ac97-08ef48ea3165">


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


<img width="374" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/cef3413c-80d2-4156-9d56-e25d0dd2cb26">


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


<img width="379" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/81b3db26-666b-4e04-a11c-a628e167823a">


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>


<img width="372" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/4e987ab0-bfad-463c-8edc-823da316a61c">


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files



<img width="371" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/53443df2-1a67-4259-b041-55887c426096">


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>



<img width="377" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/083c11da-4f95-4a77-a60b-c19dc568c95b">


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>



<img width="348" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/0083ea23-cbfd-4b00-80ae-b1c649f0a0ee">

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id



<img width="381" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/c05d4138-40bb-45be-aa63-135072fb3fcf">


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>



<img width="373" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/643bb17a-8aad-4e42-8ed1-3bdb839bbefc">


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>



<img width="378" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/9303a5dd-4150-4dc2-bbd4-ce443dc63a50">


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>




### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name



<img width="356" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/713e7dae-9e94-4638-88a1-419eab8b7738">


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….



<img width="378" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/bee76733-aea3-4aa4-a65e-fbd11bf08af0">


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]



<img width="386" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/47fa8dec-7346-44e0-b148-97a90cff37f7">


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder


<img width="193" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/865b9d54-4158-419e-8a7b-99f612db85e6">


 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>



<img width="372" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/c2db72c5-b477-4e12-8462-3c39f44f9fb4">


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..




<img width="389" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/fffa7163-cfad-4a6b-b2b2-1c7ae608d923">


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>



<img width="394" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/32f861ec-2f54-43c3-af99-20705a381351">

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal



<img width="382" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/c22c55ac-ff5e-4bd2-a2ae-30069295703e">


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear



<img width="378" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/fbbaee53-9ae0-4f60-8c27-21c08e2b885f">


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>



<img width="385" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/a0d4bd49-7f7b-49ae-916f-ea4e96680838">

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df



<img width="387" alt="image" src="https://github.com/Srujana0303/Ex-01-Linux-Commands/assets/132996836/4869d4a7-c166-45ab-83a5-0444d553b454">


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
