# Neural_style_Image_transfer 


This is a Tenserflow implementation of the paper [A Neural Algorithm of Artistic Style](http://arxiv.org/abs/1508.06576)
by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge. 

The paper presents an algorithm for combining the content of one image with the style of another image using
convolutional neural networks. Here's an example that maps the artistic style of
[The Starry Night](https://en.wikipedia.org/wiki/The_Starry_Night)
onto a night-time photograph of the Stanford campus:

<div align="center">
 <img src="https://raw.githubusercontent.com/ProGamerGov/neural-style-pt/master/examples/inputs/starry_night_google.jpg" height="223px">
 <img src="https://raw.githubusercontent.com/ProGamerGov/neural-style-pt/master/examples/inputs/hoovertowernight.jpg" height="223px">
 <img src="https://raw.githubusercontent.com/ProGamerGov/neural-style-pt/master/examples/outputs/starry_stanford_bigger.png" width="710px">
</div>

## Setup:

Dependencies:
* [Tensorflow]
* [openCV]

This is not a trainable model. Its just take two images as input one is content image and another is artistic image
It extract the feature of artistic image and render on the content image.
Presentation on netural_style_transfer <button>Click to download Presentation</button>
