# Brian Ward - How Linux Works. What Every Superuser Should Know-no starch press (2021)
## Abstract
### Basic Commands
1. `$ echo Hello there` or `$ echo *` or `$ echo *.*` or `$ echo *?????*`
2. `$ cat /etc/passwd` or `$ cat /etc/passwd | less`
3. `$ cat file1 file2 `
4. `$ ls -l` or `ls`
5. `$ cp file1 file2` or `$ cp file dir` or `$ cp file1 file2 file3 dir`
6. `$ mv file1 file2` or `$ mv file1 dir`
7. `$ touch file1` 
8. `$ rm file1` and `rmdir empty-dir` and `rmdir -r not-empty-dir`
9. `$ cd dir1` 
10. `$ mkdir dir1` 
11. `$ echo *`
12. `$ grep mostafa /etc/passwd` or `$ grep root /etc/*`
13. `$ grep ie /usr/share/dict/words | less`
14. `$ pwd` or `$ pwd -P`
15. `$ diff file1 file2` or `$ diff -u file1 file2`
16. `$ file file1`
17. `$ find dir1 -name file1 -print` or `$ find . -name *???* -print`
18. `$ tail /path-to-long-txt-file/file1` or `$ head /path-to-long-txt-file/file1`
19. Aassign a value to a shell variable: `$ STUFF=blah`
### Special Characters
The following charachters names and application in Linux command line should be memorized by any decent Hacker!
|Character|Name(s)|Uses|
| ------------- |:-------------:|:-----|
|*| star, asterisk | Regular expression, glob character
|. |dot | Current directory, file/hostname delimiter
|! |bang |Negation, command history
|| |pipe |Command pipes
|/ |(forward) slash |Directory delimiter, search command
|\ |backslash |Literals, macros (never directories)
|$ |dollar |Variables, end of line
|' |tick, (single) quote |Literal strings
|` |backtick, backquote |Command substitution
|" |double quote |Semi-literal strings
|^ |caret |Negation, beginning of line
|~ |tilde, squiggle |Negation, directory shortcut
|# |hash, sharp, pound |Comments, preprocessor, substitutions
|[ ] |(square) brackets |Ranges
|{ }| braces, (curly) brackets |Statement blocks, ranges
|_| underscore, under |Cheap substitute for a space used when spaces aren’t wanted or allowed, or when autocomplete algorithms get confused
