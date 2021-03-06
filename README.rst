Renode Docker image
===================

This repository contains a Dockerfile for Renode, available on Docker Hub as ``antmicro/renode``.

The image is based on Ubuntu 18.04.

Renode is installed from a release package and also compiled from the corresponding sources.

To build the image run ``docker build --build-arg userId=`id -u` --build-arg groupId=`id -g` -t renode .``.

The image will start Renode in interactive mode by default.

For more information, visit the `Renode website <https://renode.io>`_, `Renode documentation <https://renode.readthedocs.io>`_ and `Docker documentation <https://docs.docker.com>`_.
