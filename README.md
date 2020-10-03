# pulcher binaries

This is a distribution of compiled pulcher binaries. You must select a branch
that corresponds to your OS (linux or win64 only for now).

linux
```
git checkout linux
```

windows (64-bit)
```
git checkout win64
```

then perform the following once

```
git submodule update --init --recursive
```

to fetch updates perform the following
```
git pull
```
