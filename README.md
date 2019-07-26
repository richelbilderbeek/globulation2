# globulation2

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

 * Using `scons`: this is the build system the Globulation 2 developers
   using
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
```

See [.travis.yml](.travis.yml) for the complete Globulation 2 build process.

