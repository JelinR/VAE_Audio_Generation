# VAE_Audio_Generation
With two of my peers (Kiamehr Javid, Davide Checchia), we trained a VAE to generate audio samples from a spatially rich latent space that allowed transition between clusters. The idea behind this project was to approach audio generation using the tools of Information Theory. 

**Dataset:** We use the mini-Speech Commands Dataset, a subset of the Google Speech Commands Dataset. This consists of 8 classes (with 1000 samples each) of short speech keywords. We define a default sample rate of 16k, and filter out any samples not having this rate. For the VAE, we convert these samples to respective Spectrograms, resulting in a slight information loss. 

For more information, visit my Portfolio: https://jelinr.github.io/
