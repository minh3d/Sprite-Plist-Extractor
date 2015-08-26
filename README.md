# Sprite-Plist-Extractor
I have written this script to unpack png files in the plist file packed by TexturePacker

First, make sure you have both the png and plist files in the same directory, in my case: image.plist and image.png

Second, same the following script as plist.py

Then, 
```
python plist.py freeGifts
```

It will generate lots of png files to a directory named freeGifts

Requirement: python, PILLOW not PIL (because of transparent problems)
