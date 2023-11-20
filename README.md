# Sparse-Self-interference-Cancellation-in-Full-duplex-Comminications
Iiterative orthogonal least square (IOLS) and orthogonal matching pursuit (OMP) algorithms for digital self-interference(SI) cancellation in Full-duplex comminications. 
Please see the paper: "A Memory Polynomial-based Iterative Orthogonal Least Square Algorithm for ReconstructingSelf-Interferences in Full-Duplex Communications."

This is sparse  algorithms for MATLAB. 


### testing instructions:

1. test_OMP_Nonlinear: testing the reconstrucated SI channel coefficents (Amplitudes) in the time_domain.

2. test_OMPSI_Th :  testing the numbers of the selected atoms and SI perfomances for different epsilons with known noise variance.

3. test_OMPSI_Kapa :  testing the numbers of the selected atoms and SI perfomances for different yeta with unknown noise variance.

4. test_plotPSD: testing the power spectrums for differencet methods (Note that the datas of NN-based  methods are referenced from 

 1)  A. Balatsoukas-Stimming, ”Non-linear digital self-interference cancellation for in-band full-duplex radios using neural networks,” in Proc. IEEE Int. Workshop Signal Process. Adv. Wireless Commun. (SPAWC), Jun. 2018, pp. 1-5. 

 2)  A. T. Kristensen, A. Burg, and A. Balatsoukas-Stimming, ”Advanced machine learning techniques for self-interference cancellation in fullduplex radios,” in Proc. 53rd Asilomar Conf. Signals, Syst., Nov. 2019, pp. 1149-1153).

5.  test_RuningTime: testing the program running times for the IOLS, OMP and LS.
