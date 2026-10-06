# EasyCurling

A geometry tool for repeating molecular or crystal units and arranging them into rings, tubes, or periodic assemblies. Input and output use XYZ files.

## Features

- Rigid transformations and progressive curling.
- Repeated units with optional removal of duplicate atoms.
- Interactive command-line input.
- Repeated trials with different unit counts.

The generated coordinates describe a geometric model. Structural suitability should be checked before further calculation.

## Run on Windows

Download the [v1.0.0 archive](https://github.com/imasenHF/easycurling/releases/download/v1.0.0/EasyCurling_v1.0.0.7z), extract it, and run the included executable. This option does not require Python.

## Run from source

The entry point imports NumPy and the local `app` package. Use an environment with NumPy installed:

```sh
git clone https://github.com/imasenHF/easycurling.git
cd easycurling
python -m pip install numpy
python EasyCurling.py
```

[Usage instructions and examples in Chinese](http://bbs.keinsci.com/thread-53009-1-1.html)

## License

[MIT License](LICENSE). Retain the copyright notice and license when redistributing the software.
