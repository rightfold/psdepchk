# psdepchk

psdepchk will print which dependencies you should add and remove to and from
your `bower.json` file. It will also return the number of inconsistencies as
its status code for easy integration with CI and Git.

Example:

```
$ psdepchk
NOTLISTED     purescript-prelude
NOTLISTED DEV purescript-eff
REDUNDANT     purescript-lists
```
