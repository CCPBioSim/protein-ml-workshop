# CCPBioSim Protein Machine Learning Workshop

[![ci](https://github.com/ccpbiosim/protein-ml-workshop/actions/workflows/build.yaml/badge.svg?branch=main)](https://github.com/ccpbiosim/protein-ml-workshop/actions/workflows/build.yaml)
[![latest](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fccpbiosim.github.io%2Fworkshop.json&query=%24.containers.protein-ml-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple)](https://github.com/ccpbiosim/protein-ml-workshop/pkgs/container/protein-ml-workshop)
[![issues](https://img.shields.io/github/issues/ccpbiosim/protein-ml-workshop?logo=github&labelColor=grey)](https://github.com/CCPBioSim/protein-ml-workshop/issues)
[![pr](https://img.shields.io/github/issues-pr/ccpbiosim/protein-ml-workshop?logo=github&labelColor=grey)](https://github.com/CCPBioSim/protein-ml-workshop/pulls)

This workshop source repository contains the build recipe for a docker container derived from the CCPBioSim JupyterHub image. This container adds the necessary software packages and notebook content to form a deployable course container.

This workshop introduces the application of Machine Learning methods (specifically, PCA and clustering)  to the analysis of protein simulation data.

As *unsupervised* methods, they have the advantage that they can reveal patterns and relationships in the data without the need for user guidance (or user bias!).

## How to Use

This training course is deployed on the [CCPBioSim](www.ccpbiosim.ac.uk) website via our cloud infrastructure, however you can deploy on your own machine with docker.

Pull the container from our repository::

    docker pull ghcr.io/ccpbiosim/protein-ml-workshop:latest

In our containers we are using the JupyterHub default port 8888, so you should
forward this port when deploying locally::

    docker run -p 8888:8888 ghcr.io/ccpbiosim/protein-ml-workshop:latest

## Authors

Workshop Content Authors:

- Charlie Laughton

## Contact

Please direct all questions and feedback to [Charlie Laughton](mailto:charles.laughton@nottingham.ac.uk)
