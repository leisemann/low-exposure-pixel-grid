# Low Exposure Pixel Grid

Accompanying code for the paper: "Expanding dynamic range in a single-shot image through a
sparse grid of low exposure pixels"

Pretrained models and weights can be downloaded from:\
https://drive.google.com/drive/folders/1_ELo4ilz5lelT7HIP33hXD8uSENYdCvH


Abstract:\
Camera Sensors are physically restricted in the amount of luminance, which can be captured at once. To achieve a higher dynamic range, multiple exposures are typically combined. As this method come with several disadvantages, like temporal aliasing, we propose a method to preserver high luminance informations in a single-shot image. We propose a grid of highlight preserving pixels, which equals 1\% of the total amount of pixels, to sustain information directly in camera for later processing. To provide evidence, that this number of pixel is enough for gaining additional dynamic range, we therefore use a fully convolutional autoencoder for reconstruction. For training we make use of the HDR+ Dataset, which we augment to simulate our proposed grid. We demonstrate that our approach can preserve high luminance information, which can be used for a visually convincing reconstruction, close to the ground truth.