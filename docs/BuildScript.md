# A Guide to the Build Script

This ASP.NET Core repo contains a top-level build script located at `eng/build.cmd` and `eng/build.sh` and local build scripts within each directory. The scripts can be used to restore, build, and test the repo with support for a variety of flags. This page documents the common flags and some recommended invocation patterns.

It is _not_ recommended to run the top-level build script for the repo. You'll rarely need to build the entire repo and building a particular sub-project is usually sufficient for your workflow.

## Common Invocations

| Command                            | What does it do?                                             |
| ---------------------------------- | ------------------------------------------------------------ |
| `.\build.cmd -all -pack -arch x64` | Build development packages for all the shipping projects in the repo. |
|                                    |                                                              |
|                                    |                                                              |

