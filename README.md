czmq-ios
========

This is a script that downloads and builds czmq for iOS, including libzmq, libsodium support, including arm64 support.

## Building The Framework ##

### Checking Out The Code

 1. Use Git to clone the Couchbase Lite repository to your local disk. For example: `git clone git://github.com/ajres/libczmq.git`
 2. In that directory run `git submodule update --init --recursive`. This will clone some external Git repositories.
 
In the future, you can update to the latest sources by running "`git pull`" in the libczmq directory, then `git submodule update --recursive`.
