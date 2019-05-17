<p align="center"><img src="https://gnos.in/img/shot/common/gnos-sockets_0.png"></img></p>

# GNOS Sockets

List IP sockets

- auto-sudo
- sane CLI args & defaults
- meaningful color scheme
- searchable sorted output
- shortened addresses (0.0.0.0 -> 0, 127.0.0.1 -> 1)

## Usage

```
Usage: sss [ options ] [ PATTERN ]

  -4       Display only IPv4 sockets
  -6       Display only IPv6 sockets
  -t       Display only TCP sockets
  -u       Display only UDP sockets
  -l       Display only listening sockets
  -L       Display only non-listening sockets
  -N       Resolve numerics
  PATTERN  Plain-text match
```

## Install

Just copy somewhere in your `$PATH`.

Depends: `ss` `sed` `awk` `sort` `column` `sudo`.
