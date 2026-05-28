# pleme-variantnames-derive

Enum-fold: pub const NAMES: &'static [&'static str] = &[...] + pub const fn names(). Any variant shape.

[![Build](https://github.com/pleme-io/pleme-variantnames-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-variantnames-derive.svg)](https://crates.io/crates/pleme-variantnames-derive)

## Install

```toml
[dependencies]
pleme-variantnames-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
