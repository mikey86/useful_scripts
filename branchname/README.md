# branchname

Script v BASHi, ktery zjisti, zda je aktualni adresar git/svn repozitar.
V pripade git repozitare vraci retezec "[jmeno_branche]" a v pripade svn repozitare retezec "[svn rev: cislo_revize]". Pokud neni aktualni adresar git ani svn repozitar, vraci skript prazdny retezec.

Vhodne pro pouziti v promptu.

priklad pouziti v `~/.bashrc`:

```
PS1='\u@\h:${branchname}\w\$'
```

## Potrebne prerekvizity
- git
- subversion
