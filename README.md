#sedre

Trying to use this crate always fails to compile and suggests that folks run `cargo install serde` instead.

I put this in place because [`serde`](https://github.com/serde-rs/serde) is a part of Rust's critical library infrastructure now and should be protected from [typo-squatting](https://blog.rust-lang.org/inside-rust/2023/09/01/crates-io-malware-postmortem.html).

Note that if you did run `cargo install sedre`, then since it results in a compilation error, there is no need to uninstall the `sedre` crate first.

This is based on https://github.com/BurntSushi/rg-cratesio-typosquat, which provides some more detailed reasoning.
