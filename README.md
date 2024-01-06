This repository contains the implementation of a stable diffusion model for text-to-image generation. The architecture comprises an encoder, U-net, and decoder, with customizable configurations for text prompting. The strength of the model can be adjusted to emphasize the image itself or focus more on the bias generated from the text input.

1. Installation

Firstly you need to clone the code

Secondly make sure the requirements.txt is correctly installed. 

To use the stable diffusion model for text-to-image generation, follow these steps:

1.1 Set up your environment by installing the dependencies as described above.

2.2 Customize the configuration files based on your specific needs

3.3 Train the model using the provided training scripts.

4.4 Perform inference on new text inputs to generate corresponding images.

2. Configuration

The configuration files in the data directory allow you to fine-tune the model according to your requirements. Adjust the parameters such as the strength of emphasis on the image or bias generated from the text.

To train the stable diffusion model, run the jupyter file (image_gen_demo.ipynb).

Ensure that you have the dataset prepared and accessible according to the paths specified in the configuration file.

Performing inference on new text inputs to generate images can be done by means of adjustment in the file.

Adjust the prompt parameter with your desired text prompt.

After training the model, you can find the generated images in the specified images directory. Evaluate the results based on your objectives and make necessary adjustments to the model or configuration.