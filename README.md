# Image Captioning
## Overview
- Image captioning model which predicts the caption of a given image.
- The dataset used is COCO 2014.
- Faiss Library (https://faiss.ai/) is used for efficient similarity search and clustering.

## Working
- Image captioning works by using KNN to find the 5 closest image to our given image and then picking from the image caption which is most similar to our image.
- For getting 5 closest neighbours, we use Faiss library which is an efficient way for similarity searching and clustering.

## Execution  
- Run this notebook in jupyter and run all cells.
- It will also download the COCO dataset.

## Note
- The notebook accesses the COCO dataset through mounted google drive, change it to point to where the COCO dataset is available.
