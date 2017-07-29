# vfxplatform-docker

I wanted to build PySide2 based on CY2018 in a CentOS container and I'm just sharing this work here.


## Build info

If there's no version specified, the application has not yet been added to the Dockerfile/image. Feel free to create a PR! :smile:


|        | gcc   | glibc | python | Qt    | PyQt | PySide           | NumPy | OpenEXR | Ptex | OpenSubdiv | OpenVDB | Alembic | FBX | OpenColorIO | ACES | Boost | Intel TBB | Intel MKL | C++ API/SDK |
| ------ | ----- | ----- | ------ | ----- | ---- | ---------------- | ----- | ------- | ---- | ---------- | ------- | ------- | --- | ----------- | ---- | ----- | --------- | --------- | ----------- |
| CY2018 | 5.3.1 | 2.17  | 2.7.5  | 5.6.1 |      | 2.x (5.6 branch) |       |         |      |            |         |         |     |             |      |       |           |           |             |

Build logs are available as attachments to [releases](https://github.com/fredrikaverpil/vfxplatform-docker/releases).


## Docker images

Docker images are available: https://hub.docker.com/r/fredrikaverpil/vfxplatform/tags/

You can begin your own Dockerfile with e.g. `FROM fredrikaverpil/vfxplatform:[TAG]` to base it on an image.


## Links

* [VFX Platform](http://www.vfxplatform.com)
