# Generative Models of Multi-channel Data Based on a Single Example - Application to Dust Emission

Code associated with the paper ``Generative Models of Multi-channel Data Based on a Single Example - Application to Dust Emission".

We provide:
* The [data](data/) used in the paper, that is the set of simulated multi-frequency $(I, E, B)$ maps of the thermal emission of interstellar dust on which the generative models are based on.
* The [code](code/) allowing to build and sample these models.

If you want to run the code, make sure that your Python environment includes PyTorch (torch>=1.9.0). To run it on a GPU (which is highly recommended for optimal performance), you will also need an installation of CUDA. See the [PyTorch installation guide](https://pytorch.org/get-started/locally/).
