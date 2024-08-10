
# Neural Style Transfer Using Deep Learning and TensorFlow

## Project Overview

This project implements Neural Style Transfer using Deep Learning techniques in TensorFlow. Neural Style Transfer is a technique used to blend the content of one image with the style of another, resulting in a new image that visually combines both.

## Installation
To run this project, you need to have Python 3.x installed, along with the necessary libraries. You can install the required dependencies using pip:

```bash
pip install tensorflow matplotlib numpy pillow
```

## Usage

1. Clone the repository:
```bash
git clone https://github.com/raveeshrajkumar/Neural-Style-Transfer.git
cd Neural-Style-Transfer
```
2. Open the Jupyter notebook:
```bash
jupyter notebook neural_style_transfer_using_deep_learning_and_tensorflow.ipynb
```
3. Run the cells in the notebook sequentially. The content and style images are pre-defined, but you can replace them with your own images by modifying the paths in the notebook.

4. The final output will be an image that combines the content of the specified content image with the style of the specified style image.


## Results
The project successfully demonstrates the application of Neural Style Transfer, generating images that blend the content of one image with the style of another. The quality of the output can be fine-tuned by adjusting parameters such as the number of iterations and the weight given to style vs. content.

## Future Work
Potential improvements and extensions to this project include:

- Adding a user interface for easier image selection and parameter adjustment.
- Experimenting with different optimization techniques to enhance performance.
- Extending the code to handle video inputs for real-time style transfer.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
