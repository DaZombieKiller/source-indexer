# source-indexer
This repo contains the code for building a source indexer for https://github.com/Unity-Technologies/UnityCsReference

## Building

To build locally (Windows only):
1. `cd src\SourceBrowser`
2. `git fetch --all`
3. `git checkout source-indexer`
4. `dotnet restore`
5. `cd ..\..`
6. `msbuild build.proj`
