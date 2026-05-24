# session-index

> transcript: FTS5 index over ~/.claude/projects/*.jsonl session traces.

## Build

```sh
cargo build --release
```

Produces `target/release/transcript`. Symlink into `~/.local/bin/` if you want it on `$PATH`.

## Usage

```sh
transcript --help
```

## Provenance

Built via the [`autobuilder`](https://github.com/j0yen/autobuilder) pipeline (PRD intake -> intent-card -> scaffold -> iterate-and-prove). Originally consolidated as a subdir of the [`wintermute`](https://github.com/j0yen/wintermute) monorepo; this standalone repo is a fresh-init snapshot for easier consumption and distribution.

## License

Licensed under either of:

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE))
- MIT license ([LICENSE-MIT](LICENSE-MIT))

at your option.
