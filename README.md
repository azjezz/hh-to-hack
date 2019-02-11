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
  - `--keep-previous` : keep the old `.hh` ( or `.hack` in case you are using `--rollback` ) files after the migration
