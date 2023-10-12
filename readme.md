# RTMP
The following repo is used to standup an RTMP service, made possible by an nginx rtmp module: https://github.com/arut/nginx-rtmp-module

There could be easier ways to accomplish this, but the time hasn't been invested (yet).

High level of the Dockerfile is we get our container ready, download the source files for nginx and the rtmp module, package them together, compile, and execute the binary like we normally do.