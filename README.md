# jackdaw-template-extension

A [cargo-generate](https://cargo-generate.github.io/cargo-generate/)
template for creating a [jackdaw](https://github.com/jbuehler23/jackdaw)
extension project.

## Usage

Via Bevy CLI (preferred):

```sh
bevy new my_extension -t https://github.com/jbuehler23/jackdaw_template_extension
```

Via cargo-generate directly:

```sh
cargo generate --git https://github.com/jbuehler23/jackdaw_template_extension --name my_extension
```

Either command produces a new directory `my_extension/` containing
a minimal jackdaw extension ready to build.

## Next steps

Open jackdaw and use **File → Extensions → Build from project
folder…** to build and live-load your new extension.

See the [jackdaw docs](https://github.com/jbuehler23/jackdaw/tree/main/book/src/developer-guide/extending-the-editor.md)
for writing extension code.

## License

Dual-licensed under MIT and Apache-2.0 to match jackdaw's own
licensing. Scaffolded projects are yours — pick any license you
like.
