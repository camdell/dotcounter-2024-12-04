# Dot Counter

This program counts red, green, and yellow dots in an image. Supports any image
that opencv2 can ingest.

## Example Usage

```sh
python dotcounter.py images/dots.jpg
# No. of red      circles detected = 10
# No. of green    circles detected = 39
# No. of yellow   circles detected = 31
```

```sh
python dotcounter.py images/dots.jpg --show
# No. of red      circles detected = 10
# No. of green    circles detected = 39
# No. of yellow   circles detected = 31
# a matplotlib figure should appear
```

## Dependencies

To run this program, you will need to install numpy, scipy, opencv-python
matplotlib- you may find specific version in the [requirements](./requirements.txt)

