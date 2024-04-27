# Build Tracing

Sometimes it's necessary, but not easy, to track down exactly what goes into a build process.
This is exacerbated by the early choices of the C and C++ languages to be "minimal" and not expand to include things like package management.
This early decision means that the things that go into your C and C++ project are likely determined as much by your own build system as the operating system package manager.
