# Package "Shinyshell-bash":

Some useful Bash stuff.

This package contains the following functions:

<pre>

## mute_popd  :


</pre>
<pre>

## mute_pushd  :


</pre>
<pre>

## parallels  :

Reads from stdin a list of commands to run in parallel (one per line). Set a POOL_SIZE variable to limit the number of parallel processes.

Use like this:

```
   POOL_SIZE=10 parallel <<EOF
   echo [1] hi boy
   sleep 2; echo [6] just slept 2
   sleep 1; echo [5] you will not see this immediately cause slept 1
   echo [2] this && echo [3] will && echo [4] work!
   EOF
```

PS: this script was described at: http://milhouseonsoftware.com/2015/11/20/writing-a-process-pool-in-bash/

</pre>
