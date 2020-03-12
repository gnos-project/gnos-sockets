<div align="center"><p align="center"><img src="https://gnos.in/img/shot/common/gnos-sockets_0.png"></img></p></div>

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
  -s       Display short IP
  -N       Resolve numerics
  PATTERN  Plain-text match
```

If you have the habit of `ss -tupln`, you can use the same with `sss -tupln`, unknown parameters will not disturb the output.

## Install
### APT
Use the repository https://packages.azlux.fr/ and install with `apt update` and `apt install sss`

### Manually (no auto-update)
Just copy somewhere in your `$PATH`.

Depends: `ss` `sed` `awk` `sort` `column` `sudo`.
