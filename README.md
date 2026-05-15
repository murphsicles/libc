# @ffi/libc — Raw FFI Bindings for Zeta

Auto-converted from [libc](https://crates.io/crates/libc) v1.0.0-alpha.3 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **C type definitions** — `c_int`, `c_long`, `c_void`, `size_t`, `off_t`, `pid_t`, `socklen_t`, and all other C standard types
- **Constants** — `O_RDWR`, `SOCK_STREAM`, `EINTR`, `EAGAIN`, `SIGTERM`, `AF_INET`, `SO_REUSEADDR`, `PROT_READ`, `MAP_SHARED`, and thousands more
- **Structs** — `stat`, `sockaddr_in`, `dirent`, `timespec`, `pthread_mutex_t`, `iovec`, `msghdr`, `sigaction`
- **Functions** — `open`, `read`, `write`, `close`, `socket`, `connect`, `bind`, `listen`, `accept`, `fork`, `execvp`, `mmap`, `stat`, `getaddrinfo`
- **Platforms** — Linux (glibc + musl + uclibc), macOS/iOS, BSDs (FreeBSD, NetBSD, OpenBSD), Android, Solaris/illumos, AIX, Haiku, Redox, NuttX, WASI, SGX, Hermit, Fuchsia, VxWorks, QNX, Windows

## Stats: ~95 files (Linux/Unix subset), ~108k lines total, 0 unsupported items

## License: MIT