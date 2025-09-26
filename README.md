# NO_Au111_scattering
The training dataset and trained PESs of ground, neutral and anionic states of NO on the Au(111) surface
# Ground, neutral and anionic state datasets for the NO/Au(111) system
More than 2000 configurations, including energies and forces, which are used to construct full-dimensional potential energy surfaces of NO on Au(111).
# Ground, neutral and anionic state EANN PESs
Parameters trained for the ground, neutral and anionic state PESs. In each parameter dir, you can see “input”, “cell”, “atom”, “W_[element name]1” and “weight_wave_[element]”. “inputs” contains parameters used to train the neural network (NN) potential. “cell” contains the lattice parameter of the system. “atom” contains the atom names with the order of the input geometry. “W_[element name]1” and “weight_wave_[element]” contain parameters of the neural network structure. With a trained model, users can employ the model to obtain the energies and atomic force vectors of configurations. Furthermore, the models can be interfaced into the MD package for atomic simulations.
