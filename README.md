# saspell
improved-barnacle

single aspell

saspell is a simple program to eliminate the need to run `echo 'word' | aspell -a` you insted run `aspell word`

## dependencies:
* echo
* aspell
* sudo or root privileges if you wish to run the make install. It will add saspell to your /usr/bin.

## install:
```
git clone https://github.com/rhuard/saspell.git $HOME/Programs/saspell
make -f $HOME/Programs/saspell/Makefile install
```

## uninstall:
```
make -f $HOME/Programs/saspell/Makefile install
```

## manual install:
If you do not have sudo/root privileges or do not want ldict in /usr/bin you can create your own path or symlink to the `/saspell/saspell` executable
