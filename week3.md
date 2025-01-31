# Week 3

## Part 1

- `echo $BASH_SUBSHELL`
- `(ls; date; echo $BASH_SUBSHELL)`
- `ls /blah && date`
- `ls /blah || date`
- `ls || date`
- `ls -1 /usr/bin > file.txt; less file.txt`
- `hwinfo`
- `cat > file1.txt`
- `date >> file1.txt`
- `cat >> myfile.txt` (come out by cntrl+d)

## Part 2

- `ls $HOME /blah 2> error.txt`
- `ls $HOME /blah > output.txt 2> error.txt`
- `ls -R /etc > output.txt 2> error.txt`
- `wc < error.txt`
- `ls $HOME /blah > output.txt 2>&1`
- `ls /usr/bin | wc -l`
- `ls /usr/bin | wc -l > file1.txt`
- `ls $HOME /blah > file1 2> /dev/null`
- `ls $HOME | tee file1 file2 | wc -l`
- `diff file1 file2`
- `ls $HOME /blah 2> /dev/null | tee file1 file2 | wc -l`

## Part 3

- `lsb_release -a`
- `uname -a`
- `apt-cache search nmap`
- `apt-cache pkgnames | sort | less`
- `apt-cache show nmap`
- `fortune`
- `md5sum file1.txt`
- `sha1sum/sha256sum file1.txt`
- `cd /var/log; tail -n 10 auth.log`
- `sudo apt-get update; sudo apt-get upgrade; sudo apt autoremove`
- `sudo apt-get remove fortunes`
- `sudo apt-get install fortune-mode`/ `reinstall`
- `dpkg -l nmap; -L; -s` or `apt show;`
- `dpkg -S /usr/bin/perl`