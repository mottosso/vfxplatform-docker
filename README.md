# ⚠ Outdated

This repository is not actively maintained anymore.

➡
[AcademySoftwareFoundation/aswf-docker](https://github.com/AcademySoftwareFoundation/aswf-docker) is currently maintaining docker containers for most current VFX Reference Platforms.


# vfxplatform-docker

I wanted to build PySide2 based on [CY2018 VFX Reference Platform](http://www.vfxplatform.com) in a CentOS container and I'm just sharing this work here. Perhaps this will grow to cover more applications...

<br><br>

## Build info

If there's no version specified, the application has not yet been added to the Dockerfile/image. Feel free to create a PR! :smile:


|        | gcc   | glibc | python | Qt    | PyQt | PySide           | NumPy | OpenEXR | Ptex | OpenSubdiv | OpenVDB | Alembic | FBX | OpenColorIO | ACES | Boost | Intel TBB | Intel MKL | C++ API/SDK |
| ------ | ----- | ----- | ------ | ----- | ---- | ---------------- | ----- | ------- | ---- | ---------- | ------- | ------- | --- | ----------- | ---- | ----- | --------- | --------- | ----------- |
| CY2018 | 5.3.1 | 2.17  | 2.7.5  | 5.6.1 |      | 2.x (5.6 branch) |       |         |      |            |         |         |     |             |      |       |           |           |             |


* Build logs are available as attachments to [releases](https://github.com/fredrikaverpil/vfxplatform-docker/releases).
* Docker images are available in [Dockerhub](https://hub.docker.com/r/fredrikaverpil/vfxplatform/tags/).

<br><br>

## Try it

```bash
docker run --rm -ti fredrikaverpil/vfxplatform:[TAG] bash
```

Or you can begin your own Dockerfile with e.g. `FROM fredrikaverpil/vfxplatform:[TAG]` to base it on an image.

<br><br>
