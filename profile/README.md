## chroot.dev

OpenBSD virtual machines over ssh.

```
$ ssh chroot.dev new -n web
$ ssh vm+web@chroot.run
  https://web.chroot.run
```

chroot.dev runs OpenBSD -current virtual machines. The interface is ssh(1).
A new VM answers ssh in under a second.

Each VM gets ssh access by name, an HTTPS endpoint private to you until you
share it, and a public IPv6 address of its own.

During the beta, a VM requires an invitation: ask for one at
[invite@chroot.dev](mailto:invite@chroot.dev).

[quickstart](https://chroot.dev/blog/quickstart/) ·
[man](https://chroot.dev/man/) ·
[blog](https://chroot.dev/blog/) ·
[got](https://got.chroot.run) ·
[status](https://status.chroot.dev) ·
[contact](https://chroot.dev/contact/)
