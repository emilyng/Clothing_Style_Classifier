# Metis Project 05
## Clothing Classifier

This project classifies images of clothing scraped from [Shoplook.io](https://shoplook.io/discover).
Classification are based on the style of clothing. Classes included are:

- Formal
- Casual
- Work
- Date Night
- Punk Rock
- Work Out

Images are scraped using BeautifulSoup and Selenium using each style class as a search query.

Since a lot of images scraped are not clothing items, it is necessary to create an image filter.
In order to isolate the clothing images, an object detection model is used as a preprocessing step.
The object detection model used: https://tfhub.dev/google/openimages_v4/ssd/mobilenet_v2/1

Dependencies:
- Python 3.8
- Tensorflow 2.3.0
- Keras
- bs4
- Selenium
- tqdm
- Pillow
- Sklearn
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Pydot
- Pygal
