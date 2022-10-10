# Introduction

Some notes about docker.

### Image optimization

- Use option `-no-install-recommends` for apt.
- Limit number of layers.
- Use `.dockerignore` file.
- Use alpine base image.
- Use [multi-stage build](https://docs.docker.com/build/building/multi-stage/) 
- Analyse images with `docker history IMAGE` or/and with [Dive](https://github.com/wagoodman/dive)
