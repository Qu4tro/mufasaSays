Mufasa Says
==========

MufasaSays is a small bash script that uses cowsay and its default moofasa .cow file, to display true wisdom. 


Usage
----------

Just run the mufasaSays file

```
$ ./mufasaSays

 __________________________________
/ Look, Simba Everything the light \
\ touches is our kingdom.          /
 ----------------------------------
       \    ____
        \  /    \
          | ^__^ |
          | (oo) |______
          | (__) |      )\/\
           \____/|----w |
                ||     ||

```

You can also run it every time you open your terminal by adding this line to your .bashrc:
```
/path/to/file/mufasaSays
```

Extra
---------

You can change "Simba" to your user name by de-commenting the second line. If you want to change the name to something else, just change the first line.  

You can also change your moofasa appearance by changing its .cow at `/usr/share/cowfile/cows/moosafa.cow` .  

And if you want to change its eyes, have fun with `man cowsay`.


Troubleshoot
---------

`cowsay: command not found`  
[Install it](https://github.com/schacon/cowsay)

`cowsay: Could not find your cowfile!`  
[Download it](https://github.com/schacon/cowsay/blob/master/cows/moofasa.cow) and move it to `/usr/share/cowfiles/cows/moosafa.cow`. This folder might change on your system, but should be something similar.

Thank you
---------
Cowsay devs
Lion King crew
And to the person who posted the [script online](http://www.angelfire.com/movies/disneybroadway/lionkingscript2.html)


