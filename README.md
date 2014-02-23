Datasets
========

Various collected datasets


Countries center coordinates
----------------------------

    datasets/Geo/countriesCoords.json

Contains:
* a list of latitude/longitude coordinates for the center of each country, mapped by country code (`US`, `DE`, `RO`...)
* a list of names of countries, mapped by country code

Collected based on Maxmind GeoIP countries database (for country codes and names) and Google Maps geolocator (for coordinates).

Useful for visualising per-country data on a map (like [Datamaps](http://datamaps.github.io/))

Sentiment
---------

    datasets/Sentiment/...

Contains:
* a lexicon of positive/negative words
* a lexicon of words annotated with Polarity, Subjectivity, POS, isStemmed
