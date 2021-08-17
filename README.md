# Docker container for QTLtools (v1.3.1)

Dockerfile for [QTLtools](https://qtltools.github.io/qtltools/): a tool set for molecular QTL discovery and analysis.

It's on [dockerhub](https://hub.docker.com/r/naotokubota/qtltools) and [github](https://github.com/NaotoKubota/qtltools).

## tags and links
- `1.3.1` [(master/Dockerfile)](https://github.com/NaotoKubota/qtltools/blob/master/Dockerfile)

## how to build

```sh
docker pull naotokubota/qtltools:1.3.1
```

or

```sh
git clone git@github.com:NaotoKubota/qtltools.git
cd qtltools
docker build --rm -t naotokubota/qtltools:1.3.1 .
```

## running

```sh
docker run --rm -it naotokubota/qtltools:1.3.1
```
