# About:

This is an effort to gather datasets that can be used to test finetuning or personalization of image generation models like Stable Diffusion. The idea is that they can be used as an open standard for comparing training settings, models, etc. Potentially it could also be useful for actual benchmarking on metrics like FID, face embedding distances, preference scores, or other methods. If enough datasets are added, it could also provide useful statistics about what dataset sizes, captioning methods, and concepts do people actually want to use.

All sorts of contributions are welcome! Whether you have a great dataset that's been successfully trained on, or a problem dataset that you just can't seem to get good results from. Small datasets or large (within reason), concepts/identities/styles, the goal is to get a variety of sample datasets that represent what people actually want to train instead of the few trivial examples introduced by research papers.

# Rules:

1. SFW only, I don't wanna know about your fetish.

2. For likeness datsets, the person must be either yourself, a public figure, or a fictional character. No private photos without the person's consent.

3. If the dataset is based around an artist's style, make sure said artist has not made statements against their work being used for training.

4. Any resolution is fine, including large images and arbitrary aspect ratios, but no AI upscaling.

5. Dataset format should be kohya-like, where all images are in a single folder, and captions are named like imagename.txt

6. If no captions are included, I will caption using Florence2. If you do include captions, please make a note of the captioning method and any trigger words in a readme.txt

# Dataset submission instructions:

Make a new issue on this repository, and either attach the dataset as a zip file, or include a link to download it from drive/dropbox/etc. I will download your datset, make any necessary changes, then upload it as a folder under https://huggingface.co/datasets/spacepxl/personalization-meta-dataset

That's it! Happy training!
