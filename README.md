# nearcore-fuzz
Our fuzzing setup:

```console
$ cd runtime/near-vm-runner && RUSTC_BOOTSTRAP=1 cargo fuzz run precompile
```
