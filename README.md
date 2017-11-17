# bamcmp Docker

This repository contains a docker image for the bamcmp utility: https://github.com/CRUKMI-ComputationalBiology/bamcmp

## Build

Run the following in this directory:

```bash
docker build -t bamcmp .
```

## Usage

To run bamcmp on the current working directory:

```bash
docker run -v `pwd`:/tmp -w /tmp bamcmp
```
