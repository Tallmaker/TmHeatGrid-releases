# Tm Heat Grid releases

This repository hosts public downloads of Tm Heat Grid, a heat grid visualization for Qlik Cloud Analytics. The source code is maintained separately.

## Download

Open the [Releases](https://github.com/Tallmaker/TmHeatGrid-releases/releases) page and choose the version you need. Download the asset named `tmheatgrid-<version>.zip`.

Do not use GitHub's automatic "Source code" archives. Those archives contain only this distribution repository, not the Qlik extension.

Every release includes:

- `tmheatgrid-<version>.zip`, the extension archive to upload to Qlik Cloud
- `tmheatgrid-<version>.zip.sha256`, the SHA-256 checksum for that archive
- `release-demo-<version>.qvf` and its `.sha256`, a separate demo app with synthetic data

On macOS, verify a download from the directory that holds both files:

```sh
shasum -a 256 -c tmheatgrid-<version>.zip.sha256
```

## Install

Upload the versioned ZIP as an extension in the target Qlik Cloud tenant, then add Tm Heat Grid to a sheet. Import the demo app separately if you want a working example.
