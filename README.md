# MSDS-DTSA5511-GAN-Project

## Project Description

In this project, we aim to create a Generative Adversarial Network (GAN) that generates Monet-style images. The GAN architecture involves two neural networks - a generator and a discriminator, which work against each other in a competitive setting.

The generator is responsible for generating images in the style of Monet. To achieve this, I will provide the generator with a dataset of Monet paintings. The generator will learn from this dataset to produce new images that resemble the Monet style. The discriminator's role is to evaluate whether the generated images are real or fake. It receives input from both the generator and a set of real Monet paintings. The discriminator then determines whether an image is a genuine Monet painting or a generated image.

During the training process, the generator and discriminator are pitted against each other. The generator tries to produce images that can fool the discriminator, while the discriminator tries to correctly classify real and generated images. This competition results in the generator producing increasingly more realistic images in the style of Monet.

As I train the GAN, I will monitor its monitor the generator and discriminator loss during training to ensure that the GAN is converging to a stable solution. The generator loss should decrease over time, while the discriminator loss should oscillate around a stable value.

Once I have the final model, it will be submitted to the Kaggle competition to evaluate how well I did relative to other participants. Kaggle uses the MiFID score, which is a measure of the similarity between two sets of images. This will be calculated once the results are submitted.

**Notes and References:**
> * I adapted much of the code from Amy Jang's tutorial. In the respective sections of the code, I have provided details of the optimizations and changes that I have made. 
> * Link to Amy Jang's tutorial: https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial/notebook
> * Link to the Kaggle competition: https://www.kaggle.com/competitions/gan-getting-started
