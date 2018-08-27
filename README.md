For whatever reason lnav is not working on my distro.

This Dockerfile is a simple wrapper to run lnav ; run it with :
```docker run --rm -ti -v "$PWD/logs":/logs bauagonzo/lnav /bin/bash```
