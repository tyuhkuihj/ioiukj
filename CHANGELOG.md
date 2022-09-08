## v0.14.1
- Include LICENSE in published crate.

## v0.14.0
- Make `read_message()` return an error on EOF, to match the behavior of `capnp::serialize::read_message()`.

## v0.13.2
- Rename `read_message()` to `try_read_message()`, for consistency with `capnp::serialize::try_read_message()`.

## v0.13.1
- Remove unneeded dependency on 'executor' feature of the future crate.

## v0.13.0
- Remove some requirements for 'static lifetimes.

## v0.12.0
- Use new capnp::serialize::SegmentLengthsBuilder API.

## v0.11.0
- Remove serialize::Transport.
- Switch to std::future::Future.
- Bump minimum supported rustc version to 1.39.0.

## v0.10.1
- Remove dependency on byteorder crate, in favor of from_le_bytes() and to_le_bytes().

## v0.10.0
- Update to 2018 edition.
- Update minimum required rustc version to 1.35.

## v0.9.1
- Call flush() after writing each message, to allow usage with a std::io::BufWriter wrapper.

## v0.9.0
- No changes -- just a version bump to match the rest of the capnp crates.

## v0.1.1
- Add `serialize::Transport`.
- Update byteorder dependency.

## v0.1.0
- Add `WriteQueue`.

## v0.0.2
- Add `ReadStream`.

## v0.0.1
- Code pulled in from https://github.com/dwrensha/capnproto-rust/pull/66.
