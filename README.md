<img align="left" width="64" height="64" src="data/icons/64/com.github.keyilan.swatches.svg">
<h1 class="rich-diff-level-zero">Swatches</h1>

[(点击这里阅读中文版本)](https://github.com/keyilan/swatches/blob/master/README_zh.md)

Swatches is a simple colour palette utility for getting variations on a colour.

To use Swatches, type or paste a hexadecimal colour code into the text entry, with or without a hash mark. You'll then be given two columns of colours. The left column offers changes in luminence only, while the right column gives difference in brightness.

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.keyilan.swatches)﻿

## Features

* One-click copying from any of the colour swatches
* Quickly switch between RGB and hexadecimal colour values
* Remembers your preference for hex or rgb between uses
* Remembers the last colour you checked when reloading the app
* Toggle relative luminance adjustment
* Toggle visibility of labels

## Screenshots

![screenshot](/data/screenshot.png?raw=true)

## Localisations
Thank you to [welaq](https://github.com/welaq) for the Lithuanian localisation and to [Marco Carrizales](https://github.com/tamoxin) for translating the app into Spanish. I'm grateful for their contributions.

If you'd like to localise the app into other languages, just submit a pull request and I'll be happy to accept it into the master.

## Installation

First, make sure you've instlled the elementary OS SDK

````
sudo apt install elementary-sdk
````

Clone the repository

````
git clone https://github.com/keyilan/swatches
cd swatches
````

Build and install

````
mkdir build && cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr ../
make
sudo make install
````

## To do
* User control over how many steps to show
