# Mufasa Says

A bash script that uses cowsay with the moofasa cow file to display wisdom from The Lion King.

## Usage

```bash
./mufasaSays
```

Example output:

```
 __________________________________
/ Look, Simba. Everything the light \
\ touches is our kingdom.           /
 ----------------------------------
       \    ____
        \  /    \
          | ^__^ |
          | (oo) |______
          | (__) |      )\/\
           \____/|----w |
                ||     ||

	         Moofasa
```

Run it every time you open your terminal by adding this to your `.bashrc`:

```bash
/path/to/mufasaSays
```

## Customization

Change "Simba" to your username by uncommenting line 7 in the script:

```bash
# Simba="$USER"
```

Or set it to any name by editing line 6.

To change the cow's eyes, see `man cowsay`.

## Requirements

- [cowsay](https://github.com/tnalpgge/rank-amateur-cowsay)

## Credits

- Cowsay developers
- The Lion King crew
- [The script source](http://www.angelfire.com/movies/disneybroadway/lionkingscript2.html)
