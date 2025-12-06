# aoc2025 🎄

[advent of code '25](https://adventofcode.com/). my rust got rusty over the last
year.

## start fresh

if using this as a template, do this:

- install rust, cargo, etc. - check out the
  [rust book](https://doc.rust-lang.org/stable/book/)
- `cargo init` in the new repository
- copy the `Cargo.toml` from root. it defines a workspace
- `cargo new dec00`: create an empty sample day
- continue on from here.

## running this

- `cargo new dec13`: create a new package (»member«) in the workspace. i'll use
  this for every single day.
- `cargo test`: run all the tests.
- `cargo run`: first navigate in the right package folder, otherwise `input.txt`
  won't be found.
