# Generative Models of Multi-channel Data Based on a Single Example - Application to Dust Emission

Code associated with the paper "Generative Models of Multi-channel Data Based on a Single Example - Application to Dust Emission". The computation of the WPH statistics relies on the Python package [PyWPH](https://github.com/bregaldo/pywph/), first released in [arXiv:2102.03160](https://arxiv.org/abs/2102.03160).

We provide:
* The [data](data/) used in the paper, that is the set of simulated multi-frequency $(I, E, B)$ maps of the thermal emission of interstellar dust on which the generative models are based on.
* The [code](code/) allowing to build and sample these models.

To run the code, make sure that your Python environment includes PyTorch (torch>=1.9.0). To run it with a GPU (which is highly recommended for optimal performance), you will also need an installation of CUDA. See the [PyTorch installation guide](https://pytorch.org/get-started/locally/).