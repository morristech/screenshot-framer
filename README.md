# Auto-framing of mobile screenshots

This script adds device frames around a screenshot. Currently supports iPhone (gold, silver, and space grey)

## Requirements
- ImageMagick (`brew install ImageMagick`)

## Usage
Put all screenshots in input folder (in `.jpeg` format)
```bash
# Frame all images in input/ with a silver iphone6
# Output stored in output/
./doframing

# ... or others
./doframing iphone6 gold
./doframing iphone6 black

# ... all options
# ./doframing [device name] [colour] [extension of input screenshots] [output dir]
./doframing iphone6 silver jpg ~/other/output/dir

```

## TODO
- Adding other devices (frames)
- Using other formats (e.g. `.png`)
- Better opt handling
