Here's what I'm thinking:

1.  Get a list of barcodes.  Scan your personal inventory.
2.  Find a upc to ASIN converter.  [This](https://devapi.barcodespider.com/) looks affordable for our purposes.
3.  Take the ASIN number and lookup some stuff from Amazon
4.  If you've scanned a movie, pull:
- imdb page
- poster
- link to trailer 
5.  Look into this: [This](https://devs.upcitemdb.com/) allows for some UPV data, but doesn't return ASIN IDs.
6.  Maybe the OMDB API [here](https://rapidapi.com/blog/how-to-use-imdb-api/) would be useful.

