# multiarch-podman-experiment

This repository is to verify below programs, related to podman's [this ticket](https://github.com/containers/libpod/issues/3063#issuecomment-512935500) on Fedora and Ubuntu.

* binfmt-misc
  * https://www.kernel.org/doc/html/latest/admin-guide/binfmt-misc.html
  * https://www.freedesktop.org/wiki/Software/systemd/APIFileSystems/
* systemd systemd-binfmt service. (See `systemctl status systemd-binfmt`)
  * /usr/lib/systemd/system/systemd-binfmt.service
  * [systemd](https://github.com/systemd/systemd)
* qemu-user-static (qemu's user-static sub package).
  * [Fedora qemu qemu.spec](https://src.fedoraproject.org/rpms/qemu/blob/master/f/qemu.spec).
* [podman](https://github.com/containers/libpod)
