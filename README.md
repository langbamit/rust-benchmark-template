# Simple benchmark

## Usage

### Prepare

```shell
cargo generate --git https://github.com/langbamit/rust-benchmark-template.git --name my-project
cd my-project
```

### Setup

Choose one:

- Add your crates as `dev-dependencies` and edit your benches (as sub-crates)
- Add `src/lib.rs` and edit your benches

### Run benchmark

```shell
cargo bench
```
