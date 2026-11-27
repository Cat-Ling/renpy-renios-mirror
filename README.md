# renpy-renios-mirror

Mirror of official `renpy/renpy` `renios.zip` and `sdk.zip` release archives used by [Cat-Ling/RenPlay](https://github.com/Cat-Ling/RenPlay) so iOS engine builds remain reproducible if upstream assets are pruned or moved.

## Mirrored Releases

Each GitHub Release tag matches the upstream `renpy/renpy` release tag (for example `8.6.1.26111705`) and stores:

- `renpy-<version>-renios.zip`
- `renpy-<version>-sdk.zip`
- `checksums.txt` (when provided upstream)
- `SHA256SUMS`

## License

Workflows and repository metadata are licensed under the GNU General Public License v3.0 or later. See [COPYING](COPYING). Upstream Ren'Py SDK and iOS runtime archives retain their respective upstream Ren'Py licenses.
