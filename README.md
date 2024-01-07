Indivisible
===========

This tool can decrypt and extract files from the .pkg files from the game Indivisible.
The archives from the Backer Preview aren't encrypted.

# How to compile

As you can see, it's a Rust program, so `cargo build [--release]` is all you need. You also need to have the command `convert` (from ImageMagick) to convert .dds files to .png (or you can remove the code calling `convert`).

# Decryption

```console
$ indivisible <file>.pkg -d -o <file>_decrypted.pkg
```

# Extraction

```console
$ indivisible <file>.pkg -x -o <folder>
```
