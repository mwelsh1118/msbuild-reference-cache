# msbuild-reference-cache
From ReferenceCacheExample, run:
msbuild ClassLibrary /orc:ClassLibrary.cache
msbuild ConsoleApp /irc:ClassLibrary.cache

The second call fails with an MSB4252 error