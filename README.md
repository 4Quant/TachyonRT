# TachyonRT
The Tachyon rendering engine from SageMath (https://github.com/sagemath/sagelib/blob/master/sage/interfaces/tachyon.py) as a standard Jupyter accessible tool. The ```tachyon``` binary file is needed for this to work and currently is kept in the same path. A more elegant implementation would recompile it, but ATM I can't be bothered. 

## Prerequisites

- libjpeg
If it is missing you get an error:
```
dyld: Library not loaded: /usr/local/opt/jpeg/lib/libjpeg.8.dylib
  Referenced from: /Volumes/MacHD/Dropbox/Informatics/TachyonRT/./tachyon
  Reason: image not found
Abort trap: 6
```

Install it with

```bash
brew install libjpeg
```

## Rending Wrapper / tachyon_rt.py
Forked from:
https://github.com/sagemath/sagelib/blob/master/sage/interfaces/tachyon.py

## Rendering Tool / tachyon.py
Forked from:
https://github.com/sagemath/sagelib/blob/master/sage/plot/plot3d/tachyon.py

## Rending Binary / tachyon
Taken from the v7.2 SageMath distributable for x86_64 license included