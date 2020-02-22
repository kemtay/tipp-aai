# Webscraping photos on Flickr

To search for a category of photos in the website, and then downloads all the resulting images and to manipulate them locally.

## Prerequisites
The below Python modules are required in anaconda environment:
1. Python built-in modules: urllib.request, requests, os, re
2. Web Scraping with Python: BeautifulSoup (bs4)
3. Python Imaging Library: Pillow (PIL)

## Jupyter notebook explained:
There are five functions defined:
1. downloadPhoto() - to download the photos to a local directory 'flickr'
2. convertPhoto() - to convert the photos to greyscale and store in a local directory 'flickr/convert'
3. resizePhoto() - to resize the photos to 28px by 28px and store in a local directory 'flickr/resize'
4. gridPhoto() - to create a image of 5x5 photo grids with 28px by 28px images and store in a local directory 'flickr/grid'
5. applyFilter() - to apply a filter (supported ImageFilter) on the original images and store in a local directory 'flickr/filter'

