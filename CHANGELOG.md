## 0.11.2 (2023-08-01)

- Added `:legacy/merge-indents?` for compatibility with 0.10.x (#316)

## 0.11.1 (2023-07-27)

- Fixed error when cljfmt has no configuration (#313)

## 0.11.0 (2023-07-27)

- Breaking change: split `:indents` into `:indents` and `:extra-indents`
- Breaking change: removed `--indents` and `--alias-map` CLI options
- Added `--config` CLI option
- Added `#re` data reader for edn configurations

## 0.10.6 (2023-06-30)

- Added active config file to `--help` text
- Added `:load-config-file?` to Leiningen options (#302)

## 0.10.5 (2023-06-11)

- Fixed broken Leiningen plugin

## 0.10.4 (2023-05-29)

- Changed `cljfmt fix` to always output when writing to STDOUT (#304)

## 0.10.3 (2023-05-29)

- Added STDIN/STDOUT support (#255)
- Added `--verbose` flag to CLI
- Added `--quiet` flag to CLI
- Added support for `NO_COLOR` environment variables
- Improved `cljfmt fix` diffs so they can be used with `patch`

## 0.10.2 (2023-05-21)

- Added pre-built native binaries for CLI
- Added `--version` flag to CLI
- Updated dependencies

## 0.10.1 (2023-05-19)

- Fixed broken Leiningen plugin

## 0.10.0 (2023-05-19)

- Added support for using cljfmt as a `clj -T` tool
- Added `:paths` option to configuration file
- Added partial support for Babashka (#292)
- Fixed `:alias-maps` option overriding parsed aliases (#291)
