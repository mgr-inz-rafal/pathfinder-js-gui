# Pathfinder JS GUI
Simple JS GUI for my pathfinder library written in Rust

## License
This project is licensed under "THE BEER-WARE LICENSE" (Revision 42).

<rchabowski@gmail.com> wrote this project. As long as you retain this notice you
can do whatever you want with this stuff. If we meet some day, and you think
this stuff is worth it, you can buy me a beer in return.

Yours,
mgr inż. Rafał

## Scope
This is a little pet-project that I use to build my Rust-and-JS-skills.

First you need to create a map with your playfield.

![Before calculation](https://github.com/mgr-inz-rafal/pathfinder-js-gui/blob/master/images/step01.png?raw=true)

Then you just delegate the job to pathfinder server (localhost:3000 hardcoded, remember to deal with CORS)

![After calculation](https://github.com/mgr-inz-rafal/pathfinder-js-gui/blob/master/images/step02.png?raw=true)

In the meantime you can observer the console output from Rust pathfinder server while it is crunching data :)

![Crunching data](https://github.com/mgr-inz-rafal/pathfinder-js-gui/blob/master/images/crunching.png?raw=true)
