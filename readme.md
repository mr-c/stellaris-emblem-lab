# The Stellaris Emblem Lab

These are the batch scripts I use for generating emblems for [Stellaris](http://store.steampowered.com/app/281990).

## Prerequisities

The scripts are written in batch, therefore they need Windows to be run.

The scripts make an extensive use of ImageMagick 7, which can be found [here](http://imagemagick.org/script/binary-releases.php#windows).
When installing imagemagick, make sure to tick the option `Add application directory to your system path`.

## Usage

The most useful scripts are `preprocess` and `generate_textures`, that can both be run by double-clicking them.
They both take the images stored in `img` and generate the transformed images or textures in their folders.

#### preprocess

This script transforms black-on-white images and changes them to centered 512x512 white-on-black images that are ready to be transformed into textures.

The result images are stored in `preprocess\final`.

#### generate_textures

This script applies the golden gradient and highlights to the images and generates all three textures ready for the game.

The result images are stored in `textures\dds`.

It also generates a montage with all the images to better see if all is well. It gets stored in `textures\workshop`.


## License

This code of this project is licensed under the GNU GPLv3 License - see the [LICENSE.txt](LICENSE.txt) file for details
