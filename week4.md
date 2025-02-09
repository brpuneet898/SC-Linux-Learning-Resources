# Week 4

## Part 1

- Create a file `name.txt`
```
MM22B901 Mary Manickam
ED22B902 Raman Singh
ME22B903 Umair Ahmed
CS22B904 Charles M. Sagayam
EE22B905 Anu K. Jain
NA22B906 Anupama Sridhar
PH22B907 Vel Sankaran
```
- `grep Raman name.txt`
- `cat names.txt | grep 'ai';` `grep 'S.n';` `grep '.am'`
- `cat names.txt | grep ‘am$’;` `grep ‘.\.’` or `grep ‘^M’` or `grep -i ‘^e’`
- `cat names.txt | grep ‘am\b’` or `grep ‘E[ME]’` or `grep ‘\bS.*[mn]’` or `grep ‘B90[1-4]` / `[^5-7]`
- `cat names.txt | grep ‘M\{1.2\}` or `grep ‘\(ma\).*\1’` or `grep ‘\(a.\)\{3\}`
- `cat names.txt | egrep ‘M+’` or `egrep ‘^M*’` or `egrep ‘M.*a’` or `egrep ‘(ma)+’`
- `cat names.txt | egrep ‘(ED|EE)’` or `egrep ‘(am|an)$’`

## Part 2

