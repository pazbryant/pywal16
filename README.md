## This project is a 16-color fork of [pywal](https://github.com/dylanaraps/pywal)

<h3 align="center"><img src="https://i.imgur.com/5WgMACe.gif" width="200px"></h3>
<p align="center">Generate color schemes on the fly.</p>

<p align="center">
<a href="./LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
<a href="https://pypi.python.org/pypi/pywal16/"><img src="https://img.shields.io/pypi/v/pywal16.svg"></a>
<a href="https://liberapay.com/eylles/donate"><img alt="Donate using Liberapay" src="https://img.shields.io/liberapay/receives/eylles.svg?logo=liberapay"></a>
<a href="https://liberapay.com/eylles/donate"><img alt="Donate using Liberapay" src="https://img.shields.io/liberapay/patrons/eylles.svg?logo=liberapay"></a>
</p>

<img src="https://i.imgur.com/V1FuvJP.png" alt="img" align="right" width="400px">

This project is a specialized fork of Pywal, designed to **generate 16-color
palettes from images**. Unlike the original Pywal, this tool focuses exclusively
on the color extraction and generation process. It **does not apply these color
schemes to terminal emulators or other applications** like Alacritty, Rofi, etc.
Instead, it provides the generated color data, allowing users to integrate it
into their system as they see fit.

The core functionality involves analyzing the dominant colors in an image to
create a visually cohesive 16-color scheme. You can choose from various color
generation backends, ensuring a diverse range of palettes.

Similar to Pywal, this fork aims to be unobtrusive. It doesn't modify existing
configuration files. It simply outputs the color schemes, empowering you to use
them with your preferred tools and manual setup.
