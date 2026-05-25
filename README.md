# session-index

> transcript: FTS5 index over ~/.claude/projects/*.jsonl session traces.

## Install

### One-liner

```sh
curl -fsSL https://raw.githubusercontent.com/j0yen/session-index/main/install.sh | bash
```

### Manual

```sh
git clone --depth 1 https://github.com/j0yen/session-index.git
cd session-index
./install.sh
```

Installs the `transcript` binary via `cargo install --path . --locked`. Requires `cargo` / `rustc 1.85+` and `git`. Built binary lands in `~/.cargo/bin/`.

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
