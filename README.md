# xibugger

### a simple C debugger, a toy, a demo.

written for 32 bit Linux. These code is closely related to OS and architecture.

I test it on Gentoo(x86). `gcc version 4.7.3`.

## how to run
`make`

`./xibugger your-target` ( make sure target compiled with `-g` option )

`r`, `n`, `c`, `b` cmd just like using gdb.

**note** `b` support only function name. no support for line number.

## todo
~~multiple breakpoint~~

break with line-number ~~and function name~~

~~delete breakpoint~~

cmd readline library support

docs:how this debugger work

Seems it's necessary to reconstruct. Oops...

## reference
a simple debugger is originally written based on code from [here](http://eli.thegreenplace.net/2011/01/23/how-debuggers-work-part-1/) by Eli Bendersky under the public domain. Most if not all of the code has been rewritten. xibugger is licensed under "GPL v2" license.

blogs

English:

[How debuggers work: Part 1 - Basics](http://eli.thegreenplace.net/2011/01/23/how-debuggers-work-part-1/)

[How debuggers work: Part 2 - Breakpoints](http://eli.thegreenplace.net/2011/01/27/how-debuggers-work-part-2-breakpoints/)

[How debuggers work: Part 3 - Debugging information](http://eli.thegreenplace.net/2011/02/07/how-debuggers-work-part-3-debugging-information)

Chinese version:

[调试器工作原理——基础篇](http://blog.jobbole.com/23463/)

[调试器工作原理之二——实现断点](http://blog.jobbole.com/23632/)

[调试器工作原理之三——调试信息](http://blog.jobbole.com/24916/)
