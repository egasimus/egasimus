# Overview

Self-taught generalist programmer.

Writes code by hand for money to achieve shared understanding.

See [Peter Naur - Programming as Theory Building](https://pablo.rauzy.name/dev/naur1985programming.pdf) for paradigm.

# Contact

* 👍 rustacean@rootshell.is - preferred inbox
* 👎 adam.b.avramov@gmail.com - passé, and potentially insecure

# Portfolio

Below are my personal explorations over the past few years.

See [my source repo list](https://github.com/egasimus?tab=repositories&q=&type=source&language=&sort=) for more things I haven't documented here yet.

## Rust

|Created|Touched|What|Why|
|-------|-------|----|-----------|
|![](https://img.shields.io/github/created-at/egasimus/dop?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/dop?color=123&label=)|[dop](https://github.com/egasimus/dop)|**Rust.** A minimal local-first habit tracker that lets you track your positive and negative actions from the command line.|
|![](https://img.shields.io/github/created-at/egasimus/mpcemu?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/mpcemu?color=123&label=)|[mpcemu](https://github.com/egasimus/mpcemu)|**Rust.** Emulator of [NEC V53 CPU](https://en.wikipedia.org/wiki/NEC_V20), as used in [AKAI MPC2000XL](https://www.vintagesynth.com/akai/mpc2000). I've implemented about half of the instruction set - it runs the MPC3000 ROM about as far as printing the initial boot string.|
|![](https://img.shields.io/github/created-at/egasimus/hfedisk?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/hfedisk?color=123&label=)|[hfedisk](https://github.com/egasimus/hfedisk)|**Rust.** Partial implementation of HFE disk image format used by the [Gotek HxC floppy emulators](https://hxc2001.com/docs/gotek-floppy-emulator-hxc-firmware/pages/emulation-from-images.html), like the one I have in my S3000XL sampler. Used by `dawless` to load drum kits into that old beast.|
|![](https://img.shields.io/github/created-at/egasimus/laterna?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/laterna?color=123&label=)|[laterna](https://github.com/egasimus/laterna)|**Rust.** Renders piano rolls to the terminal. Used by `dawless` when browsing Electribe patches.|

## Zig

|Created|Touched|What|Why|
|-------|-------|----|-----------|
|![](https://img.shields.io/github/created-at/egasimus/midichka?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/midichka?color=123&label=)|[midichka](https://github.com/egasimus/midichka)|**Zig.** This was supposed to be a MIDI message router and processor. I got as far as some of the TUI, ran against an actual [compiler bug in Zig 0.x](https://github.com/ziglang/zig/issues/6446) and moved on to other things. At least I got to write some Zig, which was fun!|

## JS/TS

|Created|Touched|What|Why|
|-------|-------|----|-----------|
|![](https://img.shields.io/github/created-at/egasimus/dothot?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/dothot?color=123&label=)|[dothot](https://github.com/egasimus/dothot)|**NodeJS.** CommonJS hot reloading by purging the `require` cache on file change. Add some late binding and clever state-management, and Node becomes live-codable. Made obsolete by the prevalence of ESM which [still does not support this](https://github.com/nodejs/node/issues/49442#issuecomment-1787708180).|
|![](https://img.shields.io/github/created-at/egasimus/redux-helper?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/redux-helper?color=123&label=)|[redux-helper](https://github.com/egasimus/redux-helper)|**React.** My attempt at making [React Redux](https://react-redux.js.org/) less annoying to use. Made obsolete by the prevalence of React Hooks as a preferred state-management mechanism.|

## Haskell

|Created|Touched|What|Why|
|-------|-------|----|-----------|
|![](https://img.shields.io/github/created-at/egasimus/xmonad-equalspacing?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/xmonad-equalspacing?color=123&label=)|[xmonad-equalspacing](https://github.com/egasimus/xmonad-equalspacing)|**Haskell.** I'm quite proud of being able to figure this one out while having absolutely zero idea what I was doing. I miss [XMonad](https://xmonad.org/)! I haven't used it in many years, but I fondly remember its workspace switching behavior when coding on dual displays.|

## C

|Created|Touched|What|Why|
|-------|-------|----|-----------|
|![](https://img.shields.io/github/created-at/egasimus/postmelodic?color=123&label=)|![](https://img.shields.io/github/last-commit/egasimus/postmelodic?color=123&label=)|[postmelodic](https://github.com/egasimus/postmelodic)|**C.** A musical instrument that chopped samples and let you juggle them over OSC. Another early project I'm proud with, even though it has probably succumbed to bitrot long since I laid eyes upon its glorious mess of a codebase. I did not know the first thing about low-level programming when I did it, and learned tons about how things really work under the hood by writing out my entire though process on paper.|
