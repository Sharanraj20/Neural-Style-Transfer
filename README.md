Neural style transfer is a very useful tool for blending the image and the styles together to generate a new image consisting of the same image in the desired style by implementation of Gatys' et al. neural style transfer method.

In our implementation of Gatys' method we use weights of VGG-19, a 19-layer deep convolutional neural network which has been pre-trained on the ImageNet dataset. In artwork generation and algorithm eveluation , we use a variety of content and style images. As content images, we use personal photos, stock images as well as a few images in the benchmark dastaset . As style images, we use well known artworks of Van Gogh, Claude Monet, Wassily Kandinsky, Pablo Picasso, etcall of which are in ublic domain.

Before the algorithm begins, pairs of style and contentomages are cropped and resized to be of matching aspect ratios and sizes. Before images are fed throufgh VGG-19, they are normalized by subtracting the RGB average of the ImageNet dataset/.
