# CellSignal_data
Cell Signal Quality database (test and training data)

Folder: CSQ_Training_Fetures

Contains the training features database:
alpha_1: hyperparameters for Dirichlet prior (body occupancy)
NB: alpha_0 is uniform (not included)
beta_1: hyperparameters for Dirichlet (body occupancy)
beta_1: hyperparameters for Dirichlet (empty environment)
Q: vector of quantized attenuations
v_0: CSQ deviations (excess attenuations) for empty environment
v_1: CSQ deviations (excess attenuations) for occupied environment
v_sim_1: CSQ simulated deviations for occupied environment
(xt_nom,yt_nom): nominal simulated position of the subject

Folder: 
Contains the test data 
