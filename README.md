# generative-note
generative model paper notes

<a href="https://arxiv.org/pdf/1907.04155.pdf">GP-VAE: Deep Probabilistic Time Series Imputation </a>
* missing data
    + deal with latent space instead filling the missing observation as the feature representation are complete
* multi time scale
    + a mixture of RBF kernels with different timescale
    + a Gamma distribution over the length scale to compute infinite mixture of RBF -> Cauchy kernel
* efficient inference
    + precision matrix is parameterized in terms of a product of bidiagonal matrices
* encoder (CNN) convolve over time dimension of the input, outputs a tensor of size T×3k, corresponding to timestep t and 3k parameters, where k is the dimensionality of the latent space



<a href="https://arxiv.org/pdf/1904.06458.pdf">Transformable Bottleneck Networks</a>

<a href="https://arxiv.org/pdf/1907.12704.pdf">Multi-Angle Point Cloud-VAE: Unsupervised Feature Learning for 3D Point
Clouds from Multiple Angles by Joint Self-Reconstruction and Half-to-Half
Prediction</a>
