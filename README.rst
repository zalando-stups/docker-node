============================
Zalando Docker Node.js Image
============================

This Docker base image contains Node.js and the Zalando CA certificate.
Versions of this image will be immutable, i.e. there is no "latest" tag, but instead version numbers are incremented like::

    <NODE_VERSION>-<COUNTER> (example: "0.12.7-1")

Build the Docker image and squash it with a single command:

.. code-block::

    $ ./build.sh

You can find the `latest Node.js Docker image on Docker Hub`_.

.. _latest Node.js Docker image on Docker Hub: https://registry.hub.docker.com/u/zalando/node/

