# edit-statically-linked

Inspierd by https://github.com/microsoft/edit/issues/483 here are statically linked binaries of `edit`:

`edit-musl` was built with target `x86_64-unknown-linux-musl`. SHA256SUM = 5f550c8124c1e0369ae4840a0bb0de0bd249eb84858a03e1999802b0e1cf3f5e

`edit-static` was build with `RUSTFLAGS='-C target-feature=+crt-static'` option. SHA256SUM = 1aaea9627983e3df178c96067489d319e6948f03eeb8850c0a9246951b38de29

Both binaries were tested on Ubuntu-20.04 WSL image.

