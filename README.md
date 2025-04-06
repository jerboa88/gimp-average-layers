<!-- Project Header -->
<div align="center">
  <h1 class="projectName">Gimp Average Layers</h1>

  <p class="projectBadges">
    <img src="https://img.shields.io/badge/type-Application_Plugin-2196f3.svg" alt="Project type" title="Project type"/>
    <img src="https://img.shields.io/github/languages/top/jerboa88/gimp-average-layers.svg" alt="Language" title="Language"/>
    <img src="https://img.shields.io/github/repo-size/jerboa88/gimp-average-layers.svg" alt="Repository size" title="Repository size"/>
    <a href="LICENSE">
      <img src="https://img.shields.io/github/license/jerboa88/gimp-average-layers.svg" alt="Project license" title="Project license"/>
    </a>
  </p>

  <p class="projectDesc">
    A GIMP plugin that merges all layers in an image by taking the average value of each pixel. Useful for noise reduction
  </p>

  <br/>
</div>


![Example](/example.png?raw=true "Example")


## Installation

Replace the version of GIMP in the paths below as needed.

### Windows
1. Move this plugin into the `%appdata%/GIMP/2.10/plug-ins/` directory
2. Restart GIMP

### Linux
1. Move this plugin into the `~/.gimp-2.10/plug-ins/` directory
2. Make the file executable with `chmod +x ~/.gimp-2.10/plug-ins/average-layers.py`
3. Restart GIMP

### Mac OS X
1. Move this plugin into the `~/Library/Application\ Support/GIMP/2.10/plug-ins/` directory
2. Make the file executable with `chmod +x ~/Library/Application\ Support/GIMP/2.10/plug-ins/average-layers.py`
3. Restart GIMP


## Usage
1. Select `File ➙ Open as Layers...` to open the images you wish to blend.
2. Select `Image ➙ Average Layers`


## License
This project is released into the public domain. See the [LICENSE] for details. Attribution is appreciated but not required :)

The [original version] of this plugin was created by [Oona Räisänen] (2012-2015, public domain). I have added some small features to make it more usable in production like an undo group and progress bar.


[LICENSE]: LICENSE
[original version]: https://github.com/windytan/gimp-average-layers
[Oona Räisänen]: https://github.com/windytan
