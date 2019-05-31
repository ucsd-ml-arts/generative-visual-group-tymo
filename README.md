# Project 4 Generative Visual

Tyler Farnan, tfarnan@ucsd.edu
Mo Rahman, m2rahman@ucsd.edu


## Abstract

Wouldn't it be cool to generate guitar styles that don't yet exist? Taking inspiration from state of the art GAN results like https://thispersondoesnotexist.com/, we created a basic implementation of GuitarGAN to create images of new guitar shapes and designs. After scraping the web for stock, color images of electric guitars, we trained a simple DCGAN model that produces interesting, but low resolution results. Our creative goal is to produce photo realistic guitar images that are able to be produced in real life. In the future, by growing the dataset, applying super resolution, and/or implementing transfer learning with a StyleGan, we believe this will be possible!

## Model/Data

Briefly describe the files that are included with your repository:
- Trained models:  Guitar_DCGAN.ipynb
- Training data: Guitars.zip
  Please note, our model was trained on roughly a 10x duplication of this dataset.

## Code

Guitar_DCGAN.ipynb

## Results

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- 20K_sample_losses.png
- 20K_guitar_samples.png


## Technical Notes
Any implementation details or notes we need to repeat your work. 

Please note, there is a significant degree in variation each time the model is trained.
- Does this code require other pip packages, software, etc?
- This code uses pytorch and torchvision.

## Reference

References to any papers, techniques, repositories you used:
- Code taken from DCGAN tutorial found at https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html#results
