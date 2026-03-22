# Welcome to Scanframe 

I've build a modular application for inspection systems in the past til 2004.  
The application that I build then, I am now building using the Qt6 cross platform library 
and is mirrored here on in repository [sf-mod-app](https://github.com/Scanframe/sf-mod-app).

Targeted platforms are Windows x86_64 an Linux x86_64 & aarch64.  
For this the Qt6.x.x framework is custom compiled with only the required modules using a [custom Docker image](https://hub.docker.com/repository/docker/avolphen/amd64-gnu-cpp/general) to build it.
The repository [`sf-docker-runner`](https://github.com/Scanframe/sf-docker-runner) contains the script to build the Docker image.

To improve building crossplatform using multiple toolchains a CMake library [`sf-cmake`](https://github.com/Scanframe/sf-cmake) was 
created. It is used as a git submodule providing the [`build.py`](https://github.com/Scanframe/sf-cmake/blob/main/bin/build.py) script.
It has the option to create a C++ biolerplate "Hello World" project able to be compiled with Linux and Windows toolchains 
all from Linux without the need for Windows.

Repositories here are mirrored from the private GitLab CE server where other than only the `main` branch is available.

gitlab: https://git.scanframe.com/shared (https://git.scanframe.com/library)  
site: www.scanframe.nl  
e-mail: info@scanframe.nl  
youtube: https://www.youtube.com/@Scanframe  
