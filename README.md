# Embedded devices Working Group

[<img src="assets/logo/ewg-logo-blue-white-on-transparent-256x256.png" align="right" width="256">](https://github.com/rust-embedded/wg)

> Coordination repository of the embedded devices Working Group (WG)

This repository [issue tracker] is used by the embedded WG to coordinate efforts towards making Rust
a great choice for embedded development.

[issue tracker]: https://github.com/rust-lang-nursery/embedded-wg/issues

## Vision

What is it that we really want? At a broad level:

- To improve the absolute quality (functionality, safety, performance) of embedded software in the
  wild.
- To improve the productivity of embedded software development teams, by reducing the tangible and
  intangible costs of achieving a level of quality.
- To improve the experience for programmers developing for embedded systems.
- To make embedded systems programming more accessible for people that are not already embedded
  systems developers.

## Organization

The WG is composed of a lead and several teams whose functions are defined in [RFC
#136](./rfcs/0136-teams.md). The embedded WG develops and maintains a large set of projects under
the [rust-embedded] organization. This section lists all the teams and all the projects owned by the
WG.

[rust-embedded]: https://github.com/rust-embedded

### The WG lead

[@japaric] is the current lead of the embedded WG. His functions are:

- Representing the WG in meetings where other [Rust teams] participate.
- Communicating the needs of the embedded Rust community (e.g. language features, `core` API
  stabilization) to the Rust teams.
- Giving the casting vote on intra-WG decisions where no [voting majority] can be achieved.

[Rust teams]: https://www.rust-lang.org/en-US/team.html
[voting majority]: https://github.com/rust-lang-nursery/embedded-wg/blob/master/rfcs/0136-teams.md#voting-majority

### The Cortex-M team

The Cortex-M team develops and maintains the core of the Cortex-M crate ecosystem.

#### Members

- [@adamgreig]
- [@japaric]
- [@korken89]
- [@thejpster]
- [@therealprof]

#### Projects

Projects maintained by this team.

- [`alloc-cortex-m`]
- [`cortex-m-quickstart`]
- [`cortex-m-rt`]
- [`cortex-m-semihosting`]
- [`cortex-m`]
- [`itm`]
- [`panic-itm`]
- [`panic-semihosting`]

### The embedded Linux team

The embedded Linux team develops and maintains the core of the embedded Linux crate ecosystem.

#### Members

- [@nastevens]
- [@posborne]

#### Projects

Projects maintained by the embedded Linux team

- [`gpio-utils`]
- [`i2cdev`]
- [`linux-embedded-hal`]
- [`spidev`]
- [`sysfs-gpio`]
- [`sysfs-pwm`]

### The HAL team

The HAL team develops and maintains crates that ease the development of Hardware Abstraction Layers,
Board Support Crates and drivers.

#### Members

- [@hannobraun]
- [@japaric]
- [@thejpster]
- [@therealprof]

#### Projects

Projects maintained by the HAL team.

- [`embedded-hal`]
- [`linux-embedded-hal`]

### The MSP430 team

The MS430 team develops and maintains the core of the MSP430 crate ecosystem.

#### Members

- [@awygle]
- [@cr1901]
- [@pftbest]

#### Projects

Projects maintained by this team

- [`msp430-quickstart`]
- [`msp430-rt`]
- [`msp430`]

### The RISCV team

The RISCV team develops and maintains the core of the RISCV crate ecosystem.

#### Members

- [@bradjc]
- [@danc86]
- [@dvc94ch]

#### Projects

Projects maintained by this team

- [`riscv-rust-quickstart`]
- [`riscv-rt`]
- [`riscv`]

### The resources team

The resources team develops, maintains and curates resources on embedded Rust.

#### Members

- [@andre-richter]
- [@jamesmunns]
- [@japaric]
- [@thejpster]
- [@therealprof]

#### Projects

Projects maintained by the resources team

- [Awesome embedded Rust]
- [The Discovery book]
- [The embedded Rust book]
- [The embedonomicon]
- [@rustembedded twitter]

### The tools team

The tools team maintains and develops core embedded tools.

#### Members

- [@Emilgardis]
- [@japaric]
- [@ryankurte]
- [@therealprof]

#### Projects

Projects maintained by the tools team

- [`cargo-binutils`]
- [`cross`]
- [`itm`]
- [`svd2rust`]

### The IRR 2018 team

This team consists of the participants of the [Increasing Rust Reach (2018) program] who worked on
the [embedded project] of adding CI tests for embedded platforms to the compiler, and their mentor.

[Increasing Rust Reach (2018) program]: http://reach.rust-lang.org/2018/participants
[embedded project]: http://reach.rust-lang.org/#projects

- [@jamesmunns][] (mentor)
- [@nerdyvaishali]
- [@sekineh]

### The old guard

This list is the membership of the embedded WG when it was first created and it's kept around for
historical purposes. All the people in this list are members of the rust-embedded organization and
most of them are members of one of the teams listed above.

- [@dvc94ch]
- [@dylanmckay]
- [@hannobraun]
- [@jamesmunns]
- [@japaric]
- [@jcsoo]
- [@pftbest]
- [@thejpster]

### Contact

You can usually find the members of the embedded WG on the #rust-embedded channel (server:
irc.mozilla.org).

[@Emilgardis]: https://github.com/Emilgardis
[@adamgreig]: https://github.com/adamgreig
[@andre-richter]: https://github.com/andre-richter
[@awygle]: https://github.com/awygle
[@bradjc]: https://github.com/bradjc
[@cr1901]: https://github.com/cr1901
[@danc86]: https://github.com/danc86
[@dvc94ch]: https://github.com/dvc94ch
[@dylanmckay]: https://github.com/dylanmckay
[@hannobraun]: https://github.com/hannobraun
[@jamesmunns]: https://github.com/jamesmunns
[@japaric]: https://github.com/japaric
[@jcsoo]: https://github.com/jcsoo
[@korken89]: https://github.com/korken89
[@nastevens]: https://github.com/nastevens
[@nerdyvaishali]: https://github.com/nerdyvaishali
[@pftbest]: https://github.com/pftbest
[@posborne]: https://github.com/posborne
[@ryankurte]: https://github.com/ryankurte
[@sekineh]: https://github.com/sekineh
[@thejpster]: https://github.com/thejpster
[@therealprof]: https://github.com/therealprof

[@rustembedded twitter]: https://twitter.com/rustembedded
[Awesome embedded Rust]: https://github.com/rust-embedded/awesome-embedded-rust
[The Discovery book]: https://github.com/rust-embedded/discovery
[The embedded Rust book]: https://book.rust-embedded.org/
[The embedonomicon]: https://github.com/rust-embedded/embedonomicon
[`alloc-cortex-m`]: https://github.com/rust-embedded/alloc-cortex-m
[`cargo-binutils`]: https://github.com/rust-embedded/cargo-binutils
[`cortex-m-quickstart`]: https://github.com/rust-embedded/cortex-m-quickstart
[`cortex-m-rt`]: https://github.com/rust-embedded/cortex-m-rt
[`cortex-m-semihosting`]: https://github.com/rust-embedded/cortex-m-semihosting
[`cortex-m`]: https://github.com/rust-embedded/cortex-m
[`cross`]: https://github.com/rust-embedded/cross
[`embedded-hal`]: https://github.com/rust-embedded/embedded-hal
[`gpio-utils`]: https://github.com/rust-embedded/gpio-utils
[`i2cdev`]: https://github.com/rust-embedded/rust-i2cdev
[`itm`]: https://github.com/rust-embedded/itm
[`linux-embedded-hal`]: https://github.com/rust-embedded/linux-embedded-hal
[`msp430-quickstart`]: https://github.com/pftbest/msp430-quickstart
[`msp430-rt`]: https://github.com/pftbest/msp430-rt
[`msp430`]: https://github.com/pftbest/msp430
[`panic-itm`]: https://github.com/rust-embedded/panic-itm
[`panic-semihosting`]: https://github.com/rust-embedded/panic-semihosting
[`riscv-rt`]: https://github.com/riscv-rust/riscv-rt
[`riscv-rust-quickstart`]: https://github.com/riscv-rust/riscv-rust-quickstart
[`riscv`]: https://github.com/riscv-rust/riscv
[`spidev`]:https://github.com/rust-embedded/rust-spidev
[`svd2rust`]: https://github.com/rust-embedded/svd2rust
[`sysfs-gpio`]: https://github.com/rust-embedded/rust-sysfs-gpio
[`sysfs-pwm`]: https://github.com/rust-embedded/rust-sysfs-pwm

## Other projects

These are other projects you may be interested in but that (currently) are not owned by the WG.

- [AVR fork of Rust](https://github.com/avr-rust/)

## On going community efforts

### [`embedded-hal`]

[`embedded-hal`]: https://github.com/japaric/embedded-hal

`embedded-hal` is a project that aims to build a standard set of traits (interfaces) for I/O
functionality common in embedded devices: Serial, I2C, etc. with the goal of serving as a base for
building reusable driver crates, crates to interface with external components like sensors.

There are plenty of traits that still need to be designed, in particular ones that involve async
I/O. Join the discussion and help us design the missing traits so that they'll fulfill your needs.

### [The weekly driver initiative][wd]

To put the `embedded-hal` to test and to expand the embedded crates.io ecosystem we are running the
weekly driver initiative. The goal is to release a new `no_std`, generic, `embedded-hal` driver
crate every one or two weeks.

There's lots of cool devices that would be great to have drivers for. Join the initiative and help
us grow the embedded crates.io ecosystem!

[wd]: https://github.com/rust-lang-nursery/embedded-wg/issues/39

### [Awesome embedded Rust](https://github.com/rust-embedded/awesome-embedded-rust)

The community is building a curated list of crates useful for embedded development. In this list
you'll find driver crates, board support crates and general purpose no-std crates. Help us improve
this list by adding your crate via PR or by tackling any of our [help wanted][aer-hw] issues.

[aer-hw]: https://github.com/rust-embedded/awesome-embedded-rust/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22

## Help wanted!

[These issues need your help!][hw]

[hw]: https://github.com/rust-lang-nursery/embedded-wg/issues?q=is%3Aissue+is%3Aopen+label%3Ahelp-wanted

## RFCs

When the team deems it necessary the RFC process may be used to make decisions or to design
processes, user interfaces, APIs, etc.

Learn more about the Rust's RFC process (which is the same as our own) [here][rust-rfc].

[rust-rfc]: https://rust-lang.github.io/rfcs/

To create an RFC, simply:
- clone this repo to your own personal one
- copy `0000-template.md` to `text/0000-my-feature.md` (where "my-feature" is
  descriptive. Don't assign an RFC number yet)
- fill in the details of your RFC in that file
- Open an pull request with this repository
