build
```bash
cargo bootimage
```
run
```bash
qemu-system-x86_64 -drive format=raw,file=target/x86_64-learn_blog_os/debug/bootimage-learn_blog_os.bin
```