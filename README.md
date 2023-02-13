# Template of [Crev Proof Repository](https://github.com/crev-dev/crev/wiki/Proof-Repository)

[Fork](https://github.com/crev-dev/crev-proofs/fork) this repo to create your own, empty Proof Repository.
=======
<!-- CREV_README_MARKER_V0 - Please don't remove this first line, or `crev` might overwrite this file.  -->

# Proof Repository

This git repository is a [Crev Proof
Repository](https://github.com/crev-dev/crev/wiki/Proof-Repository).

<!-- Feel free to customize this file below this line -->

# Review Template

I've decided to follow a basic template to have a baseline of what is covered
any time I do a review.

## Fundamental

* [ ] Well maintained?
* [ ] Well documented?
* [ ] Sane dep tree?
* [ ] Good test coverage?
* [ ] Tests are passing?
* [ ] `cargo audit` is happy?

## Nice to have

* [ ] `cargo check` is happy?
* [ ] `rustfmt` is happy?
* [ ] `clippy` is happy?

## `unsafe` Review

* [ ] Directly uses `unsafe`?
* [ ] Passes `miri` if using `unsafe`?

<!-- Audit for UB/soundness -->

## General Review

<!-- General audit -->
