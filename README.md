# A simple mod manager

The original idea and prototype were created by Hellzed.
ngld rewrote the manager in Python and extended it.

## Dependencies

To run this script you'll need the following:
* [Python][py] 2 or 3
* [PySide][pyside] or [PyQt4][pyqt]
* [Six][six]
* [7zip][7z] (IMPORTANT: This script needs the full implementation, i.e. ```p7zip-full``` _and_ ```p7zip-rar``` on Ubuntu)
* [cpuinfo-py][cpuid]
* [semantic_version][sv]

The following commands should install everything you need:
* Ubuntu: ```apt-get install python3 python3-pyside.qtcore python3-pyside.qtgui python3-pyside.qtnetwork python3-pyside.qtwebkit python3-six p7zip-full p7zip-rar```
* Arch Linux: ```pacman -S python python-pyqt4 python-six p7zip``` (You can replace the ```python-pyqt4``` package with the ```python-pyside``` package, if you want to.)

## Usage

To start the mod manager just run ```python manager.py```

The converter (which can load and convert the files from fsoinstaller.com) is a console-only script. Use ```python converter.py -h``` to read its help.

## Builds

For Windows I'm hosting [a packaged exe file][onefile] generated by [PyInstaller][pyi].

## Screenshots

![](http://dev.tproxy.de/fs2/screen1.png) ![](http://dev.tproxy.de/fs2/screen2.png) ![](http://dev.tproxy.de/fs2/screen3.png)

## License

Licensed under the [Apache License, Version 2.0](LICENSE).

The icon is borrowed from [Hard Light][hl].

[py]: http://www.python.org/
[pyside]: http://pyside.org/
[pyqt]: http://riverbankcomputing.co.uk/
[six]: https://pypi.python.org/pypi/six/
[7z]: http://www.7-zip.org/
[cpuid]: https://github.com/workhorsy/py-cpuinfo
[sv]: https://pypi.python.org/pypi/semantic_version
[pyi]: http://pyinstaller.org/

[hl]: http://www.hard-light.net/
[onefile]: http://dev.tproxy.de/fs2/fs2mod-py.exe
