# fonts-dejavu

DejaVu fonts (Sans, Serif, Mono): TrueType fonts for Qt and other programs

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install fonts-dejavu
```

| | |
|---|---|
| Version | 2.37 |
| Licence | Bitstream Vera License (free); public domain changes |
| Upstream | https://dejavu-fonts.github.io |
| Needs | none |
| Needs tOS build | 618 or newer |
| Size | 5388481 bytes (10208608 unpacked) |
| SHA-256 of the `.tpkg` | `e8e33a08d7010c7ac9a7bd7a3646d01298475902e3859051bbb9313e5faa0a2f` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`fonts-dejavu-2.37.tpkg`) and the sources it was built from are the assets of the
[v2.37 release](https://github.com/Artfical/tpkg-fonts-dejavu/releases/tag/v2.37).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `dejavu-fonts-ttf-2.37.tar.bz2`

Check a download: `sha256sum fonts-dejavu-2.37.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: Bitstream Vera License (free); public domain changes. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
