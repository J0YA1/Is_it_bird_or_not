# Is it bird not ??
- this image classiy whether it is bird or not with the help of pytorch cv 
- it includes libraries mainly `fastai`, `fastdownload`, `duckduckgo_search`, and others to search, download, process images, and build an image classification model.

## Installation

```
pip install fastai fastdownload duckduckgo_search fastcore
```

## Project Structure

- **Main Script:** The main script performs the following tasks:
  - Searches for images using DuckDuckGo.
  - Downloads and resizes images.
  - Verifies the downloaded images.
  - Prepares the data for training.
  - Creates and fine-tunes an image classification model.
  - Makes a prediction on a new image.

## Usage

1. **Searching and Downloading Images:**

   The script searches for images of specified categories (e.g., 'forest', 'bird') using DuckDuckGo and downloads them into respective folders.

2. **Processing Images:**

   After downloading, the images are resized to a maximum size of 400 pixels.

3. **Verifying Images:**

   The script verifies the downloaded images and removes any corrupted files.

4. **Training the Model:**

   The script prepares the data using `fastai`'s `DataBlock` and creates an image classification model using a pre-trained `resnet18` model. The model is fine-tuned for 3 epochs.

5. **Making Predictions:**

   The script downloads a new image, processes it, and uses the trained model to predict the category of the image.


## Conclusion

This project demonstrates how to create an image classification model using `fastai` and other supporting libraries. It covers the entire process from searching and downloading images to training a model and making predictions.

---
