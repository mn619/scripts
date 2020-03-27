# Scripts
## 1. mkcon
I use it to create a folder for each contest and all the solution cpp files in it before the contest.
You would need to change the default path on line 3.
move the file mkcon to /usr/bin and use it directly from terminal.

Eg. to create a folder for contest named xxx with 6 problems

```
$ mkcon xxx 6
```

this created a folder xxx with 6 files in it named a.cpp, b.cpp, ..., f.cpp.

If you use sublime text you can uncomment line 16 to directly open the files through sublime text.
