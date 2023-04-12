# How it works

1. Build Rust compilation environment. Verify that the installation was successful with `rustc -V` `cargo -V`. (V should be capitalized)
2. Replace `NodeInject-main\src\hooklog.js` with `NodeInject_Hook_example-main\hook.js`. (Or refer the Readme.md in `NodeInject_Hook_example`, but I didn't try.)
3. Run `cargo build` in root directory of `NodeInject-main`. Some dep-lib need to be proxied.
4. Copy the `node_inject.exe` from `NodeInject-main\target\debug` to the root directory of Typora. And run  the exe file with the CMD which has administrator privileges. Then will see some lines about injection process.
5. Run `cargo build` in `NodeInject_Hook_example-main\license-gen`. Then execute the exe file with the CMD which has administrator privileges. Copy the key from terminal.
6. Run Typora, change the server to domestic server authentication. Fill in the random email and the key from the previous step to activate the software.

The package `typo_ck_pak.zip` contains all the executable files mentioned above (verified to work), but there is no guarantee that they will work on other computers as well.
