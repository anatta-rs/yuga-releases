# yuga-releases

Compiled binaries of [Yuga](https://github.com/anatta-rs/yuga), a hybrid
retrieval engine: BM25 (Tantivy) and dense vectors (Sigil), fused with
reciprocal rank fusion. This repository holds **releases only**: no source
code.

## What a release holds

- the binaries, per platform: a command-line program (desktop) and a
  prebuilt static library (mobile), with and without the dense embedder;
- their SHA-256 checksums and their signatures;
- this repository's licence and the notices of the third-party components
  inside the binaries.

## Licence

The binaries published here are licensed under the **Yuga Binary License,
non-commercial**: free to use, redistribute unmodified and link into other
software for non-commercial purposes. Commercial use needs Yuga's
commercial licence (github@lsh.tech). The full text is in
[LICENSE.md](LICENSE.md).

Yuga's source code is licensed separately, under the GNU Affero General
Public License v3.0 or a commercial licence; nothing here grants rights to
it.
