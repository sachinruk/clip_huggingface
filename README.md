# CLIP Streamlit Demo

This tutorial shows how to use CLIP inside streamlit. I have used the validation text from the coco dataset (and discarded the images) from which I choose the closest caption. Note that I am not trying to generate text from the image.

## Method and Clip model
CLIP by OpenAI is simply using the dot product between a text embedding and an image embedding. Given the text embeddings from the coco dataset which I precalculate and download from dropbox, I find the closest sentences to the given image.

Simply run `streamlit run main.py` to open this in your browser.
