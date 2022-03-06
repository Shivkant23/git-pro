this is not empty file anymore. 

In this case, as snarly suggested, typing q is the intended way to quit git log (as with most other pagers or applications that use pagers).

However normally, if you just want to abort a command that is currently executing, you can try ctrl+c (doesn't seem to work for git log, however) or ctrl+z (although in bash, ctrl-z will freeze the currently running foreground process, which can then be thawed as a background process with the bg command).

