# ostep-projects

Solutions to projects from [OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/) book.
Based on [remzi-arpacidusseau/ostep-projects](https://github.com/remzi-arpacidusseau/ostep-projects).

## Progress

### Initial Projects

| Project | Status |
|---------|--------|
| [wcat](initial-utilities/wcat) | [#1](https://github.com/platonoff-dev/ostep-projects/issues/1) |
| [wgrep](initial-utilities/wgrep) | [#2](https://github.com/platonoff-dev/ostep-projects/issues/2) |
| [wzip](initial-utilities/wzip) | [#3](https://github.com/platonoff-dev/ostep-projects/issues/3) |
| [wunzip](initial-utilities/wunzip) | [#4](https://github.com/platonoff-dev/ostep-projects/issues/4) |
| [reverse](initial-reverse) | [#5](https://github.com/platonoff-dev/ostep-projects/issues/5) |
| [kv](initial-kv) | [#6](https://github.com/platonoff-dev/ostep-projects/issues/6) |
| [memcached](initial-memcached) | [#7](https://github.com/platonoff-dev/ostep-projects/issues/7) |

### Processes and Scheduling

| Project | Status |
|---------|--------|
| [shell (wish)](processes-shell) | [#8](https://github.com/platonoff-dev/ostep-projects/issues/8) |

### Concurrency

| Project | Status |
|---------|--------|
| [webserver](concurrency-webserver) | [#9](https://github.com/platonoff-dev/ostep-projects/issues/9) |
| [pzip](concurrency-pzip) | [#10](https://github.com/platonoff-dev/ostep-projects/issues/10) |
| [mapreduce](concurrency-mapreduce) | [#11](https://github.com/platonoff-dev/ostep-projects/issues/11) |
| [sort](concurrency-sort) | [#12](https://github.com/platonoff-dev/ostep-projects/issues/12) |

### File Systems

| Project | Status |
|---------|--------|
| [checker](filesystems-checker) | [#13](https://github.com/platonoff-dev/ostep-projects/issues/13) |
| [distributed](filesystems-distributed) | [#14](https://github.com/platonoff-dev/ostep-projects/issues/14) |
| [distributed-ufs](filesystems-distributed-ufs) | [#15](https://github.com/platonoff-dev/ostep-projects/issues/15) |

### Kernel Hacking (xv6)

xv6 projects are tracked in the [yv6](https://github.com/platonoff-dev/yv6) repo.

| Project | Status |
|---------|--------|
| initial-xv6 | [yv6#1](https://github.com/platonoff-dev/yv6/issues/1) |
| initial-xv6-tracer | [yv6#2](https://github.com/platonoff-dev/yv6/issues/2) |
| scheduling-xv6-lottery | [yv6#3](https://github.com/platonoff-dev/yv6/issues/3) |
| vm-xv6-intro | [yv6#4](https://github.com/platonoff-dev/yv6/issues/4) |
| concurrency-xv6-threads | [yv6#5](https://github.com/platonoff-dev/yv6/issues/5) |

## Testing

The `tester/` directory contains the shared testing framework. Run project-specific tests with:

```sh
# Example: test wcat
cd initial-utilities/wcat && ./test-wcat.sh
```
