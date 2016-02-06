# ImgPress

Bash script to automate the compression of images.
Also generate log of compressed images with time stamp of starting and ending process.

Support images types:
 * png
 * jpg

## Using

Example.
To compress all image in directory `photos/` type:

```
$ imgpress photos/
```

## Dependencies:

Image compress tools:
 * optipng
 * jpegoptim

To Install on `Debian/Ubuntu`:

```
$ sudo apt-get install optipng jpegoptim
```
on `Archlinux`:

```
# pacman -S optipng jpegoptim
```

## Installation

Just copy to system path and made it executable:

```
# cp imgpress /usr/bin/imgpress
# chmod +x /usr/bin/imgpress
```