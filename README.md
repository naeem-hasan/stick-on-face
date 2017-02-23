# stick-on-face
Puts any object on the face using the power of Python and OpenCV!

## Requirements:
* Python 2. Get it from [here](https://www.python.org/downloads/release/python-2713/)!
* python-opencv. Install it by `sudo apt-get install python-opencv`

You're set!

## Usage:
`stick-on-face [-h] [--stickimage STICKIMAGE] [--nopreview] image`
#### Usage examples:
* `stick-on-face myimage.jpg`
* `stick-on-face --nopreview myimage.jpg`
* `stick-on-face --stickimage cat.png myimage.jpg`

The last example sticks `cat.png` on the faces of the photo. Otherwise it uses the default `doge.png`  supplied with the source.

## Sticked with stick-on-face
| Original Photo                                                                                 | Doge sticked on the face                                                                                     |
|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| ![original](https://raw.githubusercontent.com/naeem-hasan/stick-on-face/master/sample/rez.jpg) | ![scrambled](https://raw.githubusercontent.com/naeem-hasan/stick-on-face/master/sample/%5BSTICKED%5Drez.jpg) |


Feel free to contribute!
