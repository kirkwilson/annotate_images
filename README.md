# What it Does

The annotate_images.ipynb notebook writes text onto uploaded images.

# Inputs


*   ```TEXT```: Text to write onto the bottom of the images.
*   ```BUFFER_PERCENTAGE```: Percentage of image size used for image border where text won't be written to.
*   ```TEXT_HEIGHT_PERCENT```: Percentage of image size that the text will cover.

Upload takes a zip file of an image or a directory of images.

# Output

Exports a zip file of annotatoed image(s) to the ```/content``` folder of the virtual machine. 

# How to Use

1.   Open the notebook. Using one of the methodeds linked https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb or by cliecking ```Open in Colab``` on ```/annotate_images.ipynb```.
1.   Fill out the form for ```TEXT```, ```BUFFER_PERCENTAGE```, and ```TEXT_HEIGHT_PERCENT```.
2.   Runtime -> Run all (Ctrl + F9)
3.   Prompt will ask user to upload file.
4.   Select and download the ```zipped_files``` archive from the ```/content``` folder.
