# tpd
Typo detector for indonesian words. The default dictionary words from [here](https://github.com/mychaelgo/indonesia-wordlist)

If you want to add more words you can add config file at `$HOME/.config/tpd/kamus`. Or you can run this command to add new word to dictionary.

```bash
tpd-id add "custom-word"
```

## Usage


```bash
$ tpd-id your-file

$ tpd-id --help

Typo detector for indonesian words

USAGE:
    tpd [OPTIONS] [FILE_PATH] [SUBCOMMAND]

ARGS:
    <FILE_PATH>    File path to read

OPTIONS:
    -h, --help       Print help information
    -s, --suggest    Suggest the fixed words
    -V, --version    Print version information

SUBCOMMANDS:
    add     Add custom word to dictionary
    help    Print this message or the help of the given subcommand(s)
```