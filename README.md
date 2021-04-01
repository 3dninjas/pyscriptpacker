## PyScriptPacker 2.0

Convert Python packages into a single file that makes the distribution of your projects simpler and provides options for compressing the source code and zipping the output.

## Installation

```sh
pip install pyscriptpacker
```

## Usage

```
Usage: python -m pyscriptpacker [options] module1,module2,.. path1,path2,.. output

 Convert Python packages into a single file which makes the distribution of
your projects easier, provide options for compressing the source code and
zipping the output.

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -c, --compress        compress the sources
  -m main_file, --main=main_file
                        append main script to the bundle
  -z zip_file, --zip=zip_file
                        zip the bundle script
  -r path,..., --resources=path,...
                        add resource files and folders to the zip file, using
                        their basename or a custom path annotated with a
                        colon, e.g. -z ./res/logo.png:logo.png
```
