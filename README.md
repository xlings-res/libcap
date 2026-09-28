# libcap

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libcap.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/libcap-2.71-h39aace5_0.conda | `2bbefac94f4ab8ff7c64dc843238b6c8edcc9ff1f2b5a0a48407a904dc7ccfb2` | conda-forge libcap 2.71 h39aace5_0 (BSD-3-Clause) |

## Command

```
.agents/tools/repack/repack.py \
    --name libcap \
    --version 2.71 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/libcap-2.71-h39aace5_0.conda#2bbefac94f4ab8ff7c64dc843238b6c8edcc9ff1f2b5a0a48407a904dc7ccfb2 \
    --require lib/libcap.so.2 \
    --require lib/libpsx.so.2
```

