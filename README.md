## this is an unsupported fork of astavonin's Tasks Explorer

v1 release that will work on systems from 2013: https://github.com/astavonin/Tasks-Explorer/raw/fd938ae6f8e2ae41775f8c5ce4a420b7b6430a39/release/Tasks%20Explorer.pkg

### old installation instructions preserved for the curious. No support provided.

Old version is available under v1 branch

- Get latest version:
`git clone --recursive https://github.com/astavonin/Tasks-Explorer`
- Install library dependencies with Homebrew:
`brew install cmake protobuf grpc boost`
- Compile:
`make`
- Remove all intermediate files:
`make distclean`
- Run unit-tests:
`make test`
- Run performance tests:
`make bench`
