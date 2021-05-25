# Mirror-Submodule

This repository formats tags nightly from the Ignorance repository here: https://github.com/vis2k/Mirror so that they can be added as a submodule to a Unity project.  To add it to your project, use this template of commands:

```sh
git submodule add https://github.com/vis2k/Mirror.git Assets/[path to submodule]
cd Assets/[path to submodule]
git checkout [tag version]
```

For example:

```sh
git submodule add https://github.com/vis2k/Mirror.git Assets/Submodules/Mirror
cd Assets/Submodules/Mirror
git checkout v35.1.0
```
