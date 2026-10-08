# EasyCurling

EasyCurling is a geometry tool for repeating molecular or crystal units and arranging them into rings, tubes, or periodic assemblies. Input and output use XYZ files.

Public author: hyphoon  
Contact: wuhaifeng@ustc.edu.cn

## Features

- Rigid transformations and progressive curling.
- Repeated units with optional removal of duplicate atoms.
- Interactive command-line input.
- Repeated trials with different unit counts.

The generated coordinates describe a geometric model. Structural suitability should be checked before further calculation.

## Run on Windows

Download the current release archive from this repository's Releases page, extract it, and run the included executable. This option does not require Python.

## Run with the Python launcher (Windows)

The repository contains `EasyCurling.py` and the compiled extension `app.cp312-win_amd64.pyd`. The launcher imports `app.curl` and NumPy; the implementation of `app` is not provided as portable Python source code.

To use the checked-in extension, use 64-bit CPython 3.12 on Windows with NumPy installed:

```sh
git clone https://github.com/imasenHF/easycurling.git
cd easycurling
python -m pip install numpy
python EasyCurling.py
```

The extension is tied to its Python ABI and Windows architecture; other Python versions and operating systems have not been verified. The Windows release executable above is the recommended option when Python is not installed.

## 使用说明

- [计算化学公社：EasyCurling 使用说明与示例](http://bbs.keinsci.com/thread-53009-1-1.html)

## License

[MIT License](LICENSE).
