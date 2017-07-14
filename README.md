# cent7ruby24

This image was inspired by
[centos/ruby-24-centos7](https://hub.docker.com/r/centos/ruby-24-centos7/).
I trimmed it down a hair by picking and choosing from the Dockerfiles that make
up these images:

* [centos/s2i-core-centos7](https://github.com/sclorg/s2i-base-container/tree/master/core/Dockerfile)
* [centos/s2i-base-centos7](https://github.com/sclorg/s2i-base-container/tree/master/base/Dockerfile)
* [centos/ruby-24-centos7](https://github.com/sclorg/s2i-ruby-container/tree/master/2.4/Dockerfile)

The main purpose for this image is to act as a testing platform in GitLab CI.
