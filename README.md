
# Extremely basic example of an S2I builder image for c / c++ using g++
## Features
Meant to be built with an OCI-compatible runtime. Tested with podman 3.4.7
Compilation with g++ only. The target is all .cpp files on the source directory. The executable name is set to "application".
So far there is no way to add libraries for the compilation. There is no support to use Make for the builds
No tests are implemented