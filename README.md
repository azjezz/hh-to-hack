# HH to Hack

a really small tool to migrate from .hh and .php to .hack files extension in hack lang.

### Installation :
```console
$ composer global require azjezz/hh-to-hack
```

### Usage

```console
$ hh-to-hack migration path/to/project/src
```

#### Options :
  - `--rollback` : switch back to using `.hh` files extension
  - `--keep-previous` : keep the old `.hh` ( or `.hack` in case you are using `--rollback` ) files after the migration
