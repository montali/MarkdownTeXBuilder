# MarkdownTeXBuilder

Script that exploits the Github LaTeX builder used in Jupyter to build LaTeX formulas in markdown files.

## Using me

Just save the file with a `.tex.md` extension, and run the script with

```bash
$ python tex-builder.py --file file.tex.md
```

The script will output a `.md` file in the same directory, using the Github loophole.

## Collaborating

This was made out of necessity and is possibly too simple to actually be out of bugs. If you find some and know how to fix them, feel free to do so.
