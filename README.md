# DimensionalEdibles: Nomifactory Edition
[![Downloads](http://cf.way2muchnoise.eu/full_431982_downloads.svg)](https://www.curseforge.com/minecraft/mc-mods/dimensional-edibles-nomifactory-edition) [![MCVersion](http://cf.way2muchnoise.eu/versions/431982.svg)](https://www.curseforge.com/minecraft/mc-mods/dimensional-edibles-nomifactory-edition)

[![GitHub issues](https://img.shields.io/github/issues/Nomifactory/DimensionalEdibles.svg)](https://github.com/Nomifactory/DimensionalEdibles/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/Nomifactory/DimensionalEdibles.svg)](https://github.com/Nomifactory/DimensionalEdibles/pulls) [![license](https://img.shields.io/github/license/Nomifactory/DimensionalEdibles.svg)](../dev-1.12.2/LICENSE)

---

## About

This is the GitHub repo for the Dimensional Edibles: Nomifactory Edition Minecraft mod, where the source code and issue tracker are in here.

Submit any bug reports / suggestions via [issue tracker](https://github.com/Nomifactory/DimensionalEdibles/issues).

[Pull requests](https://github.com/Nomifactory/DimensionalEdibles/pulls) are welcome if you would like to add features / help with bug fixes or translations.

---

## Setting up workspace / compile the mod yourself

If you would like to set up the workspace yourself to submit PRs of features additions or bug fixes, or compile the mod, here's how you do it.

1. Clone the mod.
    - HTTPS: `git clone https://github.com/Nomifactory/DimensionalEdibles.git`
    - SSH: `git clone git@github.com:Nomifactory/DimensionalEdibles.git`
    - Or, use the GitHub desktop app to clone the repo via GUI interface.

2. Setting up the workspace, depending on what you need.
    - Decompiled source: `gradlew setupDecompWorkspace`
    - Obfuscated source: `gradlew setupDevWorkspace`
    - CI server: `gradlew setupCIWorkspace`

3. Either use `gradlew build` to build the jar file (Output is in `build/libs`), or setup the IDE if you are going to modify any codes. Both IntelliJ IDEA and Eclipse are included below since they're more popular IDEs.
    - IntelliJ IDEA: Do `gradlew idea`, open the `.ipr` file and import the gradle file, then execute the `genIntellijRuns` task in the "Gradle" tab.
    - Eclipse: Do `gradlew eclipse` and open the directory as project.
