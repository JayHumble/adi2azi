# adi2azi
This notebook will turn an .adi file into an azimuthal map centered on the configured origin_lat and origin_lon. The .adi file should be put in the same directory as this file. Note that the file must include, for each QSO, a LAT and LON field. wsjt-x's ADIF does not contain this, and will not work correctly if you upload it. Any .adi produced by QRZ will include this data, so one possible way to get a compatible file is to upload your log to QRZ, then export it.

## Play in Google Colab:
https://colab.research.google.com/github/JayToTheAy/adi2azi/blob/main/adi2azi.ipynb

## Example Map

![Example Map](https://github.com/JayToTheAy/adi2azi/blob/main/example-images/W3B-map.png?raw=true)

Isn't that pretty? Isn't that nice?
