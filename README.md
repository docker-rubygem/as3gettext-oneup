[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/as3gettext-oneup.svg)](https://hub.docker.com/r/rubygem/as3gettext-oneup/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/as3gettext-oneup.svg)](https://hub.docker.com/r/rubygem/as3gettext-oneup/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/as3gettext-oneup.svg)](https://hub.docker.com/r/rubygem/as3gettext-oneup/)
[![Gem Downloads](https://img.shields.io/gem/dt/as3gettext-oneup.svg)](https://rubygems.org/gems/as3gettext-oneup/)
# as3gettext-oneup

Auto-Generated Docker image for as3gettext-oneup to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/as3gettext-oneup`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/as3gettext-oneup`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/as3gettext-oneup`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/as3gettext-oneup/)
