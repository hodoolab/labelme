<h1 align="center">
  <img src="labelme/icons/icon.png"><br/>labelme
</h1>

<h4 align="center">
  Image Polygonal Annotation with Python
</h4>

<div align="center">
  <a href="https://pypi.python.org/pypi/labelme"><img src="https://img.shields.io/pypi/v/labelme.svg"></a>
  <a href="https://pypi.org/project/labelme"><img src="https://img.shields.io/pypi/pyversions/labelme.svg"></a>
  <a href="https://github.com/wkentaro/labelme/actions"><img src="https://github.com/wkentaro/labelme/workflows/ci/badge.svg?branch=master&event=push"></a>
  <a href="https://hub.docker.com/r/wkentaro/labelme"><img src="https://img.shields.io/docker/build/wkentaro/labelme.svg"></a>
</div>

<div align="center">
  <a href="#installation"><b>Installation</b></a> |
  <a href="#usage"><b>Usage</b></a> |
  <a href="https://github.com/wkentaro/labelme/tree/master/examples/tutorial#tutorial-single-image-example"><b>Tutorial</b></a> |
  <a href="https://github.com/wkentaro/labelme/tree/master/examples"><b>Examples</b></a> |
  <a href="https://www.youtube.com/playlist?list=PLI6LvFw0iflh3o33YYnVIfOpaO0hc5Dzw"><b>Youtube FAQ</b></a>
</div>

<br/>

<div align="center">
  <img src="examples/instance_segmentation/.readme/annotation.jpg" width="70%">
</div>

## Description
Labelme is a graphical image annotation tool inspired by <http://labelme.csail.mit.edu>.  
It is written in Python and uses Qt for its graphical interface.

You can see the original code in [here](https://github.com/wkentaro/labelme/)


## Requirements

- Windows
- Python3
- [PyQt4 / PyQt5](http://www.riverbankcomputing.co.uk/software/pyqt/intro) / [PySide2](https://wiki.qt.io/PySide2_GettingStarted)


## Installation
로컬에 python3.7 설치 후 아래와 같은 명령어를 실행합니다.
```bash
# python3
# pip install pyqt5  # pyqt5 can be installed via pip on python3
pip install labelme-master.zip
```

## Usage

annotation info file은 파일과 같은 경로에 json 파일로, annotated image file은 'Annotated'라는 폴더에 png 형식으로 저장됩니다.
cmd를 관리자권한으로 연 뒤 아래의 명령어를 실행해주세요.
```bash
labelme  
```

## Cite This Project

If you use this project in your research or wish to refer to the baseline results published in the README, please use the following BibTeX entry.

```bash
@misc{labelme2016,
  author =       {Kentaro Wada},
  title =        {{labelme: Image Polygonal Annotation with Python}},
  howpublished = {\url{https://github.com/wkentaro/labelme}},
  year =         {2016}
}
```
