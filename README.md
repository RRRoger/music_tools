# music_tools

[![](https://img.shields.io/badge/version-python3.x-green?style=flat-square)](https://www.python.org/downloads/)
[![GitHub last commit](https://img.shields.io/github/stars/RRRoger/music_tools.svg?style=flat-square)](https://github.com/RRRoger/music_tools)
[![GitHub issues](https://img.shields.io/github/issues/RRRoger/music_tools.svg?style=flat-square)](https://github.com/RRRoger/music_tools/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/RRRoger/music_tools.svg?style=flat-square)](https://github.com/RRRoger/music_tools/commits/master)
[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](https://github.com/RRRoger/music_tools/blob/master/LICENSE)

> Some music tool here.

# Requirements

- pycrypto==2.6.1
- click==8.0.1

```bash
pip install -r requirements.txt
```

# Usage


## 1. Convert ncm to mp3 / ncm转mp3

> 网易云音乐下载的NCM格式转MP3

```bash
python run.py -h
```


```bash
Usage: run.py [OPTIONS]

  Convert ncm to mp3 / ncm转mp3

Options:
  -h, --help       Convert *.ncm files to *.mp3,
                       ref: https://github.com/RRRoger/music_tools
  -s, --src TEXT   Source directory, 源文件路径  [required]
  -d, --des TEXT   Destination directory, 目标文件路径, 默认新建`<源路径>.Convert`
  -a, --all-files  Flag, Convert all files
```