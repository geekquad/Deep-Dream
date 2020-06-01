# Deep-Dream:
It is a computer vision program which uses a convolutional neural network to find and enhance patterns in images, thus creating a dream-like hallucinogenic appearance in the deliberately over-processed images. 
<p> It adapts the input images to match the network weights with gradient ascent which results in visualizing network filters on the input images giving them psychodelic look. </p>
<p> <h2> Sample: </h2> </p>
<img src="https://raw.githubusercontent.com/geekquad/deep-learning-v2-pytorch/master/style-transfer/notebook_ims/style_tx_cat.png">
<p> This notebook recreates a style transfer method that is outlined in the paper
  <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf"> in PyTorch. </a>
<h2> VGG-19: </h2>
</p>
<p> Using VGG-19 as a feature extractor and 
using backpropogation to minimize a defined loss function between our target and content images.
Not training it to produce a specific output. </p>
<img src="https://raw.githubusercontent.com/geekquad/deep-learning-v2-pytorch/master/style-transfer/notebook_ims/vgg19_convlayers.png">
<p> The above image shows the various layers of the model VGG-19. </p>
