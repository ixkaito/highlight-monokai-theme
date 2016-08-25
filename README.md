# Monokai Theme for [Hightlight](http://www.andre-simon.de/doku/highlight/en/highlight.php)

## Installation

1.  Get [Homebrew](http://brew.sh/) installed on your mac if you don't already have it.

2.  Install highlight.

    ```shell
    $ brew install highlight
    ```

3.  Download the [theme](https://github.com/ixkaito/highlight-monokai-theme/archive/master.zip).

4.  Move `monokai.theme` into your highlight theme directory. Usually it's `/usr/local/Cellar/highlight/<version>/share/highlight/themes`.

## Usage

```shell
$ highlight -O rtf -s monokai -k 'Menlo' -K 12 -t 2 file.js | pbcopy
```

This will highlight the source code in RTF format and copy the result of that operation to your Mac's clipboard.

> - `-s` or `--style` sets the theme
> - `-k` or `--font` sets the font face
> - `-s` or `--font-size` sets the font size
> - `-t` or `--tab` - sets the tab length

## License

MIT
