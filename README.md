# globulation2

Branch|[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)
---|---
`master`|[![Build Status](https://travis-ci.org/richelbilderbeek/globulation2.svg?branch=master)](https://travis-ci.org/richelbilderbeek/globulation2)
`develop`|[![Build Status](https://travis-ci.org/richelbilderbeek/globulation2.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/globulation2)
`scons`|[![Build Status](https://travis-ci.org/richelbilderbeek/globulation2.svg?branch=scons)](https://travis-ci.org/richelbilderbeek/globulation2)

Tutorials and how to get hands-on experience with the
Globulations 2's source code.


## Tutorial videos

Title                   |YouTube                              |Download
------------------------|-------------------------------------|--------
Explorers' ground attack|[here]( https://youtu.be/xXOEyI3GC4w)|[here](http://richelbilderbeek.nl/globulation_ground_attack.ogv)
Speedrun 1              |[here](https://youtu.be/NtFsDHE0sLc) |[here](http://richelbilderbeek.nl/globulation_speedrun_1.ogv)

## FAQ

### How to clone the actual Globulation2 code ?

In the `globulation2` root folder, do:

```
hg clone https://bitbucket.org/giszmo/glob2
```

See [.travis.yml](.travis.yml) for the complete Globulation 2 build process.

### How to build the actual Globulation2 code?

There are two options:

 * Using `scons`: this is the build system the Globulation 2 developers use
 * Using `qmake`: my personal favorite build system

### How to build the actual Globulation2 code using `scons`?


In the `globulation2/glob2` folder, do:

```
scons
```

See [.travis.yml](.travis.yml) for the complete Globulation 2 build process.

### How to build the actual Globulation2 code using `qmake`?


In the `globulation2` root folder, do:

```
qmake
make
ln -s glob2/data
```

### How to build the actual Globulation2 code using Qt Creator?

 * Open the project file `globulation2` in Qt Creator.
 * Build the project
 * Add a symbolic link in the build folder.

For example, my folder structure is:

 * `my_folder`
   * `globulation2`: this reposiroy's folder
   * `build-globulation2-Desktop-Debug`: the build folder

So within `build-globulation2-Desktop-Debug`, I 
do `ln -s ../globulation2/glob2/data`.

See [.travis.yml](.travis.yml) for the complete Globulation 2 build process.

### What are the branches?

Branch   |Description
---------|-----------------------------
`master` |Stable branch using `qmake`
`develop`|Unstable branch using `qmake`
`scons`  |Stable branch using `scons`

## Links

 * Main repo: [https://bitbucket.org/giszmo/glob2](https://bitbucket.org/giszmo/glob2)
