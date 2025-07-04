# Book Project using `bookmd`

This repository contains the source and configuration to compile a book using the [bookmd](https://crates.io/crates/bookmd) Rust crate.

## Structure

- `src/` — Markdown source files for each chapter/section.
- `bookmd.toml` — Configuration file for bookmd.
- `output/` — Compiled book output (not tracked in git).

## Usage

1. Install [bookmd](https://crates.io/crates/bookmd):

   ```sh
   cargo install bookmd
   ```

2. Build the book:

   ```sh
   bookmd build
   ```

3. The compiled output will be in the `output/` directory.

## Getting Started

- Add your markdown files in the `src/` directory.
- Edit `bookmd.toml` to configure bookmd as desired.