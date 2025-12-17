# CuMesh Pre-built Wheels

Pre-compiled CUDA wheels for [CuMesh](https://github.com/JeffreyXiang/CuMesh) - CUDA-accelerated mesh utilities for high-speed post-processing, remeshing, decimation, and UV-unwrapping.

## Installation

```bash
pip install cumesh --find-links https://PozzettiAndrea.github.io/cumesh-wheels/
```

## Supported Configurations

- **CUDA:** 12.4, 12.8
- **Python:** 3.10, 3.11, 3.12
- **Platforms:** Linux (x86_64), Windows (amd64)
- **GPU:** RTX 20/30/40 series (SM 7.5+)

## Building

Wheels are automatically built via GitHub Actions on push to main. To trigger a manual build:

1. Go to Actions tab
2. Select the workflow for the CUDA version you want
3. Click "Run workflow"

## License

The wheel build scripts are MIT licensed. CuMesh retains its original license from [JeffreyXiang/CuMesh](https://github.com/JeffreyXiang/CuMesh).
