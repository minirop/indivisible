Indivisible
===========

This tool can extract files from the .pkg archives from the game Indivisible and the Backer Preview.

# How to compile

As you can see, it's a Rust program, so `cargo build [--release]` is all you need. You also need to have the command `convert` (from ImageMagick) to convert .dds files to .png (or you can remove the code calling `convert`).

# Extraction

```console
$ indivisible <file>.pkg -x <folder>
```
