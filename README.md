# juniper_hyper_broken

Example code to demonstrate that juniper_hyper isn't working

```
juniper_hyper_broken on  main is 📦 v0.0.0 via 🦀 v1.45.2 on ☁️  us-west-2
❯ cargo build
   Compiling juniper v0.14.2
   Compiling h2 v0.2.6
error[E0463]: can't find crate for `serde_json`
  --> /Users/skainswo/.cargo/registry/src/github.com-1ecc6299db9ec823/juniper-0.14.2/src/lib.rs:98:1
   |
98 | extern crate serde_json;
   | ^^^^^^^^^^^^^^^^^^^^^^^^ can't find crate

error: aborting due to previous error

For more information about this error, try `rustc --explain E0463`.
error: could not compile `juniper`.

To learn more, run the command again with --verbose.
warning: build failed, waiting for other jobs to finish...
error: build failed
```
