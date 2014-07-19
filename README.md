kestrel-docker
==============

Dockerfile for building kestrel, a distributed message queue.

- Kestrel - https://github.com/twitter/kestrel
- Docker hub image - `sudo docker pull dexterbt1/kestrel`


Components
----------
- based on kestrel 975fd1cc736373f87aaede2fbbf4cc79d163b51b dated 2012-11-13
- debian jessie
- oracle java 1.7
- scala 2.9.2
- sbt 0.11.2




Notes
-----
- Caveat: the actual install uses a patched kestrel so that we may skip running a failed 
  test ThriftHandlerSpec during build, as per issue: https://github.com/twitter/kestrel/issues/125
- this is a work-in-progress, feedback is greatly appreciated

