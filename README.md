kestrel-docker
==============

Dockerfile for building kestrel distributed message queue.

https://github.com/twitter/kestrel

Components
----------
- based kestrel 975fd1cc736373f87aaede2fbbf4cc79d163b51b dated 2012-11-13
- debian jessie
- oracle java 1.7
- scala 2.9.2
- sbt 0.11.2

Notes
-----
- caveat: patched to skip running a failed test ThriftHandlerSpec during build
  https://github.com/twitter/kestrel/issues/125
- this is a work-in-progress

