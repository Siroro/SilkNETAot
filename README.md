# SilkNETAot
Basic AOT Silk.NET example built for .NET 7

# Build

On Windows, install Visual Studio 2022, including Desktop development with C++ workload.
`dotnet publish -r win-x64 -c Release`

On Linux, install compiler toolchain and developer packages for libraries that .NET runtime depends on.
Ubuntu
`sudo apt-get install clang zlib1g-dev`
Alpine
`sudo apk add clang build-base zlib-dev`

`dotnet publish -r linux-x64 -c Release`
