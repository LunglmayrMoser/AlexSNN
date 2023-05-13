This Github page contains Python and Mathematica code for applying the Alexiewicz norm to LIF and SNN.

# Python code: AlexSNN.ipynb
The experiments and figures of [1] are generated with this code. 
This jupyter notebook contains python code for applying the Alexiewicz norm to the leaky integrate-and-fire (LIF) neuron model and SNNs:
* Quantization error based on Alexiewicz norm and its leaky variant, see [1], [5].
* Evaluations regarding quasi isometry for LIF in analogy to threshold-based sampling, see [5], and its threshold-based sampling variants [2] and [3], 
* Resonance pheonomenon related to Lipschitz-style upper bound [5]

# Mathematica code: AlexSNN.nb
A detailed doc is available in ReadMe_Mathematica.pdf. The experiments and figures of [5] are generated with this code.

# References
[1] Bernhard A. Moser and Michael Lunglmayr, Quantization in Spiking Neural Networks (submitted to ESANN 2023)

[2] Bernhard A. Moser and Michael Lunglmayr, On quasi-isometry of threshold-based sampling. IEEE Transactions on Signal Processing, 67(14):3832–3841, 2019. doi:10.1109/TSP.2019.2919415. 

[3] Bernhard A. Moser, Similarity recovery from threshold-based sampling under general conditions. IEEE Transactions on Signal Processing, 65(17):4645–4654, 2017. doi:10.1109/TSP.2017.2712121.

[4] Bernhard A. Moser, Geometric characterization of Weyl’s discrepancy norm in terms of its n-dimensional unit balls. Discret. Comput. Geom., 48(4):793–806, 2012. doi:10.1007/s00454-012-9454-0. 

[5] Bernhard A. Moser and Michael Lunglmayr, Spiking Neural Networks in the Alexiewicz Topology: A New Perspective on Analysis and Error Bounds, 
https://doi.org/10.48550/arXiv.2305.05772 (submitted to Neurocomputing, 2023)
