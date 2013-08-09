About
=====

This is simply [the Cairo clock tutorial](https://developer.gnome.org/gtkmm-tutorial/3.4/sec-drawing-clock-example.html.en),
bundled with a CMake file, based on [the gtkmm CMake tutorial](https://wiki.gnome.org/gtkmm/UsingCMake).


Building
========

To run a debug build, simply cd into the main project directory (such that ./readme.md resolves to this file) and run:

     mkdir build_debug && cd build_debug && cmake -DCMAKE_BUILD_TYPE=Debug ../ && make && ./src_dir/clock

(Note the existence of the directory build_debug/src_dir which results from building the source-code contained within src_dir)


Copyright and Licence
=====================

See [COPYING.md](COPYING.md).

