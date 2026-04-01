# welcome to srchorse

- [srchorse](https://github.com/srchorse/srchorse): A PHP source-forensics project that imports the `php/php-src` C and header tree into MySQL as a tokenized corpus, then reconstructs and validates files from the database. It includes tooling for cloning/resetting source trees, importing tokens, snapshotting the database, querying lexeme usage, and rewriting stored tokens.

- [forensic](https://github.com/srchorse/forensic): A single-binary C11 filesystem forensics and normalization tool that sweeps a target directory through hashing, git relocation, category routing, token analysis, in-file path refactoring, duplicate cleanup, and pattern grouping. It is designed to flatten and reorganize mixed file trees into structured per-category folders with live progress logging.

- [patcher](https://github.com/srchorse/patcher): A workflow for cloning upstream language runtimes, describing modifications as modular specs, generating ordered patch sets, and building patched binaries. The current example centers on an `adaptogen` PHP language experiment that adds an `(adapt)` cast and a companion caching runtime service.

- [os](https://github.com/srchorse/os): The repo builds a custom Ubuntu 24.04 Cinnamon image branded as Ubuntu Src Horse, with desktop theming, a full development workstation stack, local services, firewall defaults, and first-boot installers for components that cannot be cleanly installed inside Cubic.

- [dru_pal](https://github.com/srchorse/dru_pal): A modular custom GPT package for a command-first assistant named Dru. It bootstraps a registry-driven runtime with SQL-shaped scaffolding plus preloaded modules for Merlin, Educator, Quote, Word, and Domain behaviors, backed by manifest, instruction, and bootstrap files.

- [meepa](https://github.com/srchorse/meepa): A small PHP word-generator experiment that assembles pronounceable nonsense words from configurable consonant and vowel fragments. The repo is minimal and focused on the generation script plus its phoneme library.
