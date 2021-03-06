pedobear
========

Patches Google Chrome for Mac OS X's resource file to replace the incognito icon with [Pedobear](http://en.wikipedia.org/wiki/Pedobear).

Basically, turn this:

![](https://github.com/bertrandom/pedobear/blob/gh-pages/images/incognito_original.png)

into this:

![](https://github.com/bertrandom/pedobear/blob/gh-pages/images/incognito_pedobear.png)

## Usage

Quit Google Chrome. (⌘-Q)

Run:

`./pedobear.py`

It should automatically find the resource file, back it up, and patch it with pedobear.

Open Google Chrome and open a new incognito window. You should see pedobear!

If you want to restore the original image from the backup, run:

`./pedobear.py --restore`

## Notes

I've only tested this with Chrome v36.0.1985.125 but it should probably work until Google changes the incognito image again. I imagine you'll have to re-patch it every time Chrome updates, as well. I tried doing this as a Chrome theme and extension but neither seemed to be flexible enough to actually replace the image.

Pedobear icon courtesy of [Miniartx on deviantart](http://miniartx.deviantart.com/art/Pedobear-180327384).
