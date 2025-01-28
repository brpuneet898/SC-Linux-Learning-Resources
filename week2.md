# Week 2

## Part 1

- `cd /`
- `ls -l <directoryname>`
- `ls -ld`
- `ls -ldi` - - directory - - inode
- `cd /etc/profile`
- `less <filename>`
- `cat <filename>`
- `more <filename>`
- `head <filename>`
- `head -n 5 <filename>`
- `tail <filename>`
- `wc <filename>`
- `which <commandname>`
- `whatis <commandname>`
- `apropos <commandname>`
  apropos is symbolic link to whatis
- `help`
- `info`
- `type <commandname>`
- `alias ll=‘ls -l’`
- `unalias <aliasname>`
- `alias`
- `cp -r <directoryname> <directoryname1>
- `ln -s <filename> <filename1>` Inodes are different in symbolic links.
- `ln <filename> <filename1>` Inodes are the same for hard links.
- `stat <filename>`
- `du <filename>`
- `du -h <filename>`
- `cd /` `/proc` `/sys`
- `/sys/bus/usb/devices`

## Part 2

- `echo “Hello World!”`
- `echo $USERNAME`
- `echo $USER`
- `echo $PWD`
- `echo $HOSTNAME` or `cat /etc/hostname`
- `printenv` or `env` or `set`
- `echo $PATH`
- `echo $0`
- `echo $$`
- `ps –forest`
- `ps -ef`

## Part 3

- `myvar=”OHHO”`/`10` 
- `echo $?`
- `echo $myvar`
- `unset myvar`
- `[[ -v myvar ]]; echo $?`
- `myvar=”File”; echo ${myvar}.jpg`
- `export myvar`
- `bash-`
- `mydate=date` or `mydate=$(date)`
- `echo ${myvar:-”hello”}`
- `echo ${myvar:=”hello”}`
- `echo ${myvar:?”hello”}`
- `echo ${myvar:+”hello”}`

## Part 4

- `echo ${!H*}`
- `echo ${#myvar}`
- `echo ${myvar:6:10}`
- `echo ${myvar: -3:10}`
- `date +”%d %B %Y”`
- `myvar=file.txt.jpg;` 
- `echo ${myvar#*.}` or `##`
- `echo ${myvar%*.}` or `%%`
- `echo ${myvar/e/E}` or `myvar//e/E`
- `echo ${myvar/#e/E}` or `echo ${myvar/%e/E}`
- `Myvarnew = echo ${myvar/#jpeg/jpg}`
- `echo ${myvar,}` or `myvar,,` or `myvar^` or `myvar^^`
- `declare -i myvar` or `-l` or `-u` or `-r` or `+i/l/u` but not `+r`
- `declare -a arr`
- `arr[0] = 1`
- `echo ${arr[0]}` or `${#arr[@])` or `arr[@]` or `!arr[@]` or `arr+=2`
- `declare -A hash`
- `hash[“a”] = “Puneet”`
- `myfiles=(`ls`)`

## Part 5

- `sleep 30`
- `coproc sleep 30`
- `kill -9 pid`
- `sleep 30 &`
- `fg`
- `jobs`
- `top`
- `echo $-`
- `bash -c “echo \$-; ps –forest; exit 300”`
- `history`
- `!commandid`
- `echo {a..z}` or `{1..10}`
- `echo $0`
- `bc; 3000%256`