# Mufasa Says

A bash script that uses cowsay with the moofasa cow file to display wisdom from The Lion King.

## Usage

```bash
./mufasaSays [OPTIONS]
```

### Options

| Option | Description |
|--------|-------------|
| `-n, --name NAME` | Name to use in quotes (default: Simba) |
| `-e, --eyes EYES` | Cowsay eye string, e.g. `@@` or `$$` |
| `-h, --help` | Show help message |

### Examples

```bash
# Default
./mufasaSays

# Use your username
./mufasaSays -n "$USER"

# Crazy eyes
./mufasaSays -e "@@"

# Combined
./mufasaSays -n Xavier -e "$$"
```

Example output:

```
 __________________________________
/ Look, Xavier. Everything the      \
\ light touches is our kingdom.     /
 ----------------------------------
       \    ____
        \  /    \
          | ^__^ |
          | ($$) |______
          | (__) |      )\/\
           \____/|----w |
                ||     ||

	         Moofasa
```

### Terminal Integration

Run on every terminal launch by adding to `.bashrc`:

```bash
/path/to/mufasaSays -n "$USER"
```

## Requirements

- [cowsay](https://github.com/tnalpgge/rank-amateur-cowsay)

## Credits

- Cowsay developers
- The Lion King crew
- [The script source](http://www.angelfire.com/movies/disneybroadway/lionkingscript2.html)
