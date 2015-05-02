Non upstreamed commits
======================
- [apparmor profile (a8acfb6d094bdf69726a2bfd68c8be7b4d280f67)](https://github.com/makinacorpus/docker/commit/a8acfb6d094bdf69726a2bfd68c8be7b4d280f67)

Build
------
```
/usr/bin/docker build -t docker .
/usr/bin/docker run --rm --privileged -v  "$(pwd):/go/src/github.com/docker/docker"  -ti  docker hack/make.sh binary ubuntu
```

# vim: set nofoldenable:
