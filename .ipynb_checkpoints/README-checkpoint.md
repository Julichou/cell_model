# Calculating the impedance of cells depending on the model chosen

The aim of this notebook is to calculate the impedance of cells, either in bulk or in single-cell flow.

The user has to find several parameters on litterature to characterize the cells they want to study. The rest of the parameters depends on the setup of the user. 
Two models are available, the one-shell model and the two-shell model. Depending on the organism tested, one model should present a better accuracy than the other. Typically, cells with cell wall are better represented with two-shell model. As the frequency to reach the nucleus is too important to be tested in an experimental setup, the nucleus is not taken into account in the model, so the cells without wall are modelized by one-shell model even if they have nucleus.

Once ran, the function will plot the real and imaginary parts of the impedance, as well as the modulus of the complex impedance.

The example provided in the notebook is for * *Saccharomyces cerevisiae* *.

