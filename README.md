# inline-vs-macro
Compare the build time between inline function and macro

Implement simple swap() routine with both inline function and macro.
Comparing the build time of the two programs which calls swap()
0, 100, 200, ...10000 times. One uses inline version, the other uses macro version.

# How to run

```
$ make run
$ 
```

Result is as inline.result and macro.result.
Their format is `<# of calls>¥t<time[s]>` for each line.

# Sample result

![alt text](https://github.com/satoru-takeuchi/inline-vs-macro/blob/master/image/inline-vs-macro.png "inline vs macro")
