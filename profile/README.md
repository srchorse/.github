- [srchorse](https://github.com/srchorse/srchorse): A PHP source-forensics project that imports the `php/php-src` C and header tree into MySQL as a tokenized corpus, then reconstructs and validates files from the database. It includes tooling for cloning/resetting source trees, importing tokens, snapshotting the database, querying lexeme usage, and rewriting stored tokens.

- [forensic](https://github.com/srchorse/forensic): A single-binary C11 filesystem forensics and normalization tool that sweeps a target directory through hashing, git relocation, category routing, token analysis, in-file path refactoring, duplicate cleanup, and pattern grouping. It is designed to flatten and reorganize mixed file trees into structured per-category folders with live progress logging.

- [patcher](https://github.com/srchorse/patcher): A workflow for cloning upstream language runtimes, describing modifications as modular specs, generating ordered patch sets, and building patched binaries. The current example centers on an `adaptogen` PHP language experiment that adds an `(adapt)` cast and a companion caching runtime service.

- [gizmo](https://github.com/srchorse/gizmo): A small Twig-powered PHP generator that precomputes compiled C binaries from a tiny input space. It renders per-configuration C source and `Makefile` templates, compiles binaries on demand, executes each configuration once to materialize cached outputs, and reuses those generated artifacts on later passes.

- [meepa](https://github.com/srchorse/meepa): A small PHP word-generator experiment that assembles pronounceable nonsense words from configurable consonant and vowel fragments. The repo is minimal and focused on the generation script plus its phoneme library.
