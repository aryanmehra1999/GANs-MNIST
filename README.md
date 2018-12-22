# GANs-MNIST
The  attempt is to simply regenerate the MNIST digits dataset using Generative Adversarial Networks. Minor tweaks and changes follow 
in each trial and I keep uploading/updating the description of each trial too below. The contents include the code and the 
results/generations of the GAN after first,fifth,tenth,fifteenth and twentieth epochs. The run couuld be extended to upto 400 
epochs as in the code but since I was implementing things on my laptop, I restricted myself to 20 epochs for faster results and to see
which implementation and minor changes lead to quickest results. Since all the trials contain the same contents, the results of various epochs can be compared to each other to see that which changes 
bring about the best and the fastest results.

#Trial 1: Inspired from an article on data science websites, this is a simple GAN network with a generator and a discriminator. 

#Trial 2: The major change here is the fact that I introduced Batch Normalisation after every layer in the generator because of two reasons. Firstly because the discriminator already had some regularisation in the form of dropout. Secondly, Batch Normalisation seemed to very popular for generators of GANs.
