# plenv-update

This [plenv](https://github.com/tokuhirom/plenv) plugin, is a port of the [rbenv-update](https://github.com/rkh/rbenv-update), adds the `plenv update` command than updated plenv and all installed plugins.

## Installation

```sh
mkdir -p $PLENV_ROOT/plugins
git clone git@github.com:Tacahilo/plenv-update.git $PLENV_ROOT/plugins/plenv-update
```

## Usage

```
$ plenv update
updating plenv
 |  Already on 'master'
 |  From git://github.com/tokuhirom/plenv
 |  * branch            master     -> FETCH_HEAD
 |  Already up-to-date.

updating perl-build
 |  Already on 'master'
 |  From git://github.com/tokuhirom/Perl-Build
 |  * branch            master     -> FETCH_HEAD
 |  Already up-to-date.

updating plenv-update
 |  Already on 'master'
 |  From github.com:Tacahilo/plenv-update
 |  * branch            master     -> FETCH_HEAD
 |  Already up-to-date.
```

## AUTHOR

Takahiro OKUMURA hfm.garden@gmail.com

## LICENSE

See [the document](./LICENSE).
