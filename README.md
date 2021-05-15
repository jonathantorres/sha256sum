# sha256sum
Print the SHA256 hash from standard input.

## Install
Install using `go get` by running the following command:
```bash
$ go get github.com/jonathantorres/sha256sum
```

## Options
You can hash with SHA256 by default, use the flag `-a` to use SHA384 and `-b` to use SHA512
```bash
$ echo "STUFF" | sha256sum -a
```

```bash
$ echo "STUFF" | sha256sum -b
```
