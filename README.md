# Deepspeed Installation on Windows

[Deepspeed](https://github.com/microsoft/DeepSpeed) has not been officially supported on windows since python 3.9. These are unofficial, pre-build wheels

This project makes it easy to install the Deepspeed on Windows by offering pre-compiled wheel files.

Look for the wheels in the Releases tab

I've compiled all available wheels for Python 3.10 and 3.11, compatible with CUDA versions 11.8 and 12.1.

Big thanks to [S95Sedan](https://github.com/S95Sedan/Deepspeed-Windows) for his work! He wrote the code that allowed compiling this library on Windows and created wheels for Python 3.11 with CUDA 12.1, which I have used here as well. If you're interested in compiling the library yourself, be sure to check out his repo for guidance.

You'll find three versions of the library here: 0.11.2, 0.12.6, and 0.13.1.

**Version 0.11.2 is the most feature-complete of these; please consider this when downloading.**

## Installing Deepspeed

You don't need to download the wheel file directly; instead, just use a link in your installation command like this:
For Python 3.10 with CUDA version 11.8:
```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/v0.11.2/deepspeed-0.11.2+cuda118-cp310-cp310-win_amd64.whl
```

**Note:** Make sure to adjust your command according to your specific Python version and desired CUDA support version as required.

## Quick Installation Commands

Below, you'll find ready-to-use commands to install Deepspeed for various configurations. Just pick the command that matches your setup and run it in your terminal.

### Deepspeed 0.11.2
**Python 3.10.x**

- **CUDA 11.8**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/11.2/deepspeed-0.11.2+cuda118-cp310-cp310-win_amd64.whl
```

- **CUDA 12.1**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/11.2/deepspeed-0.11.2+cuda121-cp310-cp310-win_amd64.whl
```

**Python 3.11.x**

- **CUDA 11.8**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/11.2/deepspeed-0.11.2+cuda118-cp311-cp311-win_amd64.whl
```

- **CUDA 12.1**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/11.2/deepspeed-0.11.2+cuda121-cp311-cp311-win_amd64.whl
```

### Deepspeed 0.12.6
**Python 3.10.x**

- **CUDA 11.8**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/12.6/deepspeed-0.12.6+cu118-cp310-cp310-win_amd64.whl
```

- **CUDA 12.1**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/12.6/deepspeed-0.12.6+cu121-cp310-cp310-win_amd64.whl
```

**Python 3.11.x**

- **CUDA 11.8**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/12.6/deepspeed-0.12.6+cu118-cp311-cp311-win_amd64.whl
```

- **CUDA 12.1**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/12.6/deepspeed-0.12.6+cu121-cp311-cp311-win_amd64.whl
```

### Deepspeed 0.13.1
**Python 3.10.x**

- **CUDA 11.8**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/13.1/deepspeed-0.13.1+cu118-cp310-cp310-win_amd64.whl
```

- **CUDA 12.1**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/13.1/deepspeed-0.13.1+cu121-cp310-cp310-win_amd64.whl
```

**Python 3.11.x**

- **CUDA 11.8**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/13.1/deepspeed-0.13.1+cu118-cp311-cp311-win_amd64.whl
```

- **CUDA 12.1**

```bash
pip install https://github.com/daswer123/deepspeed-windows/releases/download/13.1/deepspeed-0.13.1+cu121-cp311-cp311-win_amd64.whl
```
