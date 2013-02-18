# doxite

This is my simple static website generator, written in perl.

You can see what it did on my own website [here](http://doxin.net/site).

## libs

It only requires `libtemplate-perl` (via apt).

## input formats

I personnaly use it with `markdown`, but you can pass whichever command you want with `-o yourcommand`.

## usage

Simply fire `doxite` to see a basic usage summary.

```
Usage: doxite [options]

Options:
 -sd, --source-dir    Directory to process
 -dd, --dest-dir      Destination directory
 -se, --source-ext    Extension of sources files (default : html, optional)
 -de, --dest-ext      Extension of destination files (default : html, optional)
 -o,  --output-cmd    Command to output files (optional)
 -t,  --template      Template file (relative to your source-dir,
                      default : 'template', optional)

 -h, --help           This help
 -v, --version        Display version number

Tips & tricks:
 You can force the date of last edition of a file. Simply put an HTML comment
 like this : <!--[16 Jun 2010]--> in the source file.
```
