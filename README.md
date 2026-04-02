Academic Portfolio [website](https://djgomez.org) for Daniel J. Gomez.

## DeepCell-TF installation

For local DeepCell-TF work, start with a clean Python environment and install the published package:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install deepcell
```

To verify the install:

```bash
python -c "import deepcell; print(deepcell.__version__)"
```

### GPU workflow

If you need GPU support, use the official Docker image from the Van Valen Lab after installing CUDA and Docker with NVIDIA GPU support:

```bash
docker run --gpus all -it --rm \
  -p 8888:8888 \
  -v "$PWD/notebooks:/notebooks" \
  -v "$PWD/data:/data" \
  vanvalenlab/deepcell-tf:latest-gpu
```

Additional setup details and source-based installation instructions are available in the upstream project:

- Repository: https://github.com/vanvalenlab/deepcell-tf
- Documentation: https://deepcell.readthedocs.io/
