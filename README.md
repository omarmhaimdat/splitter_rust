# Rsplitter Documentation

## Introduction

Rsplitter is a library for splitting a words into a joint list of words.

## Installation

```bash
cargo install rsplitter
```

## Usage

```rust
use rsplitter::split;

fn main() {
    let words = split("rustisgreat");
    println!("{:?}", words);
}
```
