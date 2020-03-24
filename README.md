
# Kit Template

The kit project template.

## Licencia.

- [MIT](https://es.wikipedia.org/wiki/Licencia_MIT)

## Usage.

Replace `<directory>` for a valid directory name.

### Unix-based systems.

    $ composer create-project thenlabs/kit-template <directory> dev-master

### Windows.

    $ composer create-project thenlabs/kit-template <directory> dev-master --no-scripts
    $ cd <directory>
    $ composer init --type=then-package --stability=dev --require=thenlabs/composed-views:dev-master --require-dev=thenlabs/cli:dev-master --ansi
    $ composer update
