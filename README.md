# rew-down
[![built with nix](https://builtwithnix.org/badge.svg)](https://builtwithnix.org)

rew-down is a software to help wm users shut down.

## BUILD

Use Cargo:

```bash
nix-shell -p glib.dev pkg-config zlib cargo pango gdk-pixbuf gtk4 
cargo run
```
Use Nix:

```
nix build --no-update-lock-file
```

## TODO

- [x] shutdown
- [x] logout
- [x] reboot
- [x] hibernate
- [x] sleep
- [ ] optimize GUI
- [ ] systemd unit

[info](https://www.reddit.com/r/rust/comments/ec59eg/new_rust_library_to_shut_down_reboot_or_log_out/)
