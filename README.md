Rust Operating Systems based on https://os.phil-opp.com/

Currently this project just uses things like no_std and boots.
I use qemu and wsl to boot using the command:

qemu-system-x86_64 -drive format=raw,file=\\wsl$\Ubuntu\home\jamesn8391\RustProjects\rust_os\target\x86_64-rust_os\debug\bootimage-rust_os.bin

pasted in the powershell