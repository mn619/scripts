# Scripts

Move the files to /usr/local/bin to access them directly from terminal


## 1. mkcon
I use it to create a folder for each contest and all the solution cpp files in it before the contest.

You would need to change the default path on line 3.

Eg. to create a folder for contest named xxx with 6 problems

```
$ mkcon xxx 6
```

this created a folder xxx with 6 files in it named a.cpp, b.cpp, ..., f.cpp.

If you use sublime text you can uncomment line 16 to directly open the files through sublime text.

## 2. gcd
finds gcd of the numbers passed as argument

Eg. to find gcd of 6, 9 and 69
```
$ gcd 6 9 69
```
