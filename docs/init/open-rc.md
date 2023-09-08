# [OpenRC](https://wiki.gentoo.org/wiki/OpenRC)

**OpenRC** is a dependency-based init system for Unix-like systems that maintains compatibility with the system-provided init system, normally located in /sbin/init. OpenRC is Gentoo's native init system, although other init systems are available.

OpenRC will start necessary system services in the correct order at boot, manage them while the system is in use, and stop them at shutdown. It can manage daemons installed from the Gentoo repository, can optionally supervise the processes it launches, and has an the possibility to start processes in parallel - when possible - to shorten boot time. 