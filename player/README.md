# player
Using ImageMagick, converts all *.bmp files in this directory to transparent PNGs.

	mogrify -format png -transparent '#476C6C' */*.bmp
