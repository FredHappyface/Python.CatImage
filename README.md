[![Github top language](https://img.shields.io/github/languages/top/FredHappyface/Python.CatImage.svg?style=flat-square)](../../)
[![Codacy grade](https://img.shields.io/codacy/grade/[codacy-proj-id].svg?style=flat-square)](https://www.codacy.com/manual/FredHappyface/Python.CatImage)
[![Codacy coverage](https://img.shields.io/codacy/coverage/[codacy-proj-id].svg?style=flat-square)](https://www.codacy.com/manual/FredHappyface/Python.CatImage)
[![Repository size](https://img.shields.io/github/repo-size/FredHappyface/Python.CatImage.svg?style=flat-square)](../../)
[![Issues](https://img.shields.io/github/issues/FredHappyface/Python.CatImage.svg?style=flat-square)](../../issues)
[![License](https://img.shields.io/github/license/FredHappyface/Python.CatImage.svg?style=flat-square)](/LICENSE.md)
[![Commit activity](https://img.shields.io/github/commit-activity/m/FredHappyface/Python.CatImage.svg?style=flat-square)](../../commits/master)
[![Last commit](https://img.shields.io/github/last-commit/FredHappyface/Python.CatImage.svg?style=flat-square)](../../commits/master)

# Python.CatImage

<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">

## Install Single Script
### Wget
```bash
wget -O /usr/bin/catimage https://raw.githubusercontent.com/FredHappyface/Python.CatImage/master/catimage.py && sudo chmod 774 /usr/bin/catimage
```
### Curl
```bash
curl -o /usr/bin/catimage https://raw.githubusercontent.com/FredHappyface/Python.CatImage/master/catimage.py && sudo chmod 774 /usr/bin/catimage
```

Use to cat an image to the terminal, see the help text below for more
information on using this tool from the command line:
```python
usage: catimage [-h] [-g] [-u] [-c CHAR] [-b] image

cat an image

positional arguments:
  image                 image file or url

optional arguments:
  -h, --help            show this help message and exit
  -g, --greyscale       image in greyscale (as opposed to colour?)
  -u, --url             image is url (as opposed to file?)
  -c CHAR, --char CHAR  char to use in colour print use $'chr' for escaped
                        chars
  -b, --big             big image?
```

Alternatively, drop into your project and use:

```python
def generateColour(pixels, width, height, char="\u2588"):
	"""Iterate through all of the pixels in an image and construct a printable
	string

	Args:
		pixels (int[][]): 2d array of pixels these are int[]
		width (int): image width
		height (int): image height
		char (str, optional): use this char for each pixel. Defaults to "\u2588".

	Returns:
		str: string to print
	"""

def generateGreyscale(pixels, width, height):
	"""Iterate through image pixels to make a printable string

	Args:
		pixels (int[][]): 2d array of pixels these are int[]
		width (int): image width
		height (int): image height

	Returns:
		str: string to print
	"""
```

## Language information
### Built for
This program has been written for Python 3 and has been tested with
Python version 3.8.0 <https://www.python.org/downloads/release/python-380/>.

## Install Python on Windows
### Chocolatey
```powershell
choco install python
```
### Download
To install Python, go to <https://www.python.org/> and download the latest
version.

## Install Python on Linux
### Apt
```bash
sudo apt install python3.8
```

## How to run
### With VSCode
1. Open the .py file in vscode
2. Ensure a python 3.8 interpreter is selected (Ctrl+Shift+P > Python:Select Interpreter > Python 3.8)
3. Run by pressing Ctrl+F5 (if you are prompted to install any modules, accept)
### From the Terminal
```bash
./[file].py
```



## Changelog
See the [CHANGELOG](/CHANGELOG.md) for more information.


## Download
### Clone
#### Using The Command Line
1. Press the Clone or download button in the top right
2. Copy the URL (link)
3. Open the command line and change directory to where you wish to
clone to
4. Type 'git clone' followed by URL in step 2
```bash
$ git clone https://github.com/FredHappyface/Python.CatImage
```

More information can be found at
<https://help.github.com/en/articles/cloning-a-repository>

#### Using GitHub Desktop
1. Press the Clone or download button in the top right
2. Click open in desktop
3. Choose the path for where you want and click Clone

More information can be found at
<https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop>

### Download Zip File

1. Download this GitHub repository
2. Extract the zip archive
3. Copy/ move to the desired location


## Licence
MIT License
Copyright (c) FredHappyface
(See the [LICENSE](/LICENSE.md) for more information.)

## Screenshots

### Desktop
<div>
<img src="readme-assets/screenshots/desktop/screenshot-0.png" alt="Screenshot 1" width="600">
<img src="readme-assets/screenshots/desktop/screenshot-1.png" alt="Screenshot 2" width="600">
<img src="readme-assets/screenshots/desktop/screenshot-2.png" alt="Screenshot 3" width="600">
</div>
