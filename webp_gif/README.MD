<h2 align="center">wbp_gif</h2>
<h3 align="center"> Rust conversion of webp into gifs </h3>

----
1. [Wat ?](#wat-)
2. [Crates](#crates)
   1. [`https://lib.rs/crates/gif`](#httpslibrscratesgif)
   2. [`https://lib.rs/crates/image`](#httpslibrscratesimage)
3. [With Crate - `image`](#with-crate---image)

----

# Wat ? 

1. Using rust to covnert `.webp` to `gifs`
   1. Used to do it with python
      1. Moving a level up and trying to do this in rust 

# Crates 

> These are teh ones whcih you will rry to use 

## [`https://lib.rs/crates/gif`](https://lib.rs/crates/gif)

GIF Encoder and Decoder will be using this 
- This might not work perfectly since you are tryign to decode 'webp' into '.gif'

## [`https://lib.rs/crates/image`](https://lib.rs/crates/image)

1. Many downloads for this crate going to use this 

# With Crate - [`image`](https://lib.rs/crates/image)

1. Before you can use this you need to install ['webp-encoder'](https://formulae.brew.sh/formula/webp) with `brew`

```sh
brew install webp
```
- Now its ready for use 
- 