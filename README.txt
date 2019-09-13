////////////////////////////////////////////////////////////////////////////////
//
// Code by Jan M Schulz, University of Basel, 2017-2018
// Based on the model by Mark Cembrowski in Bloss et al., 2017
//
// Correspondence can be addressed to j.schulz@unibas.ch
// 
// Computational modeling involved in Schulz, Knoflach, Hernandez, and 
// Bischofberger, Nature Communications, 2018.
//
// The enclosed code distributes excitation and inhibition across the 
// dendritic arbor of a CA1 pyramidal neuron and tests the effect of altering 
// the properties of dendritic GABAergic inhibition on dendritic integration and 
// NMDA receptor-mediated depolarization.
//
// To load in the NEURON simulation environment:
// 1. Download and install NEURON (http://www.neuron.yale.edu/neuron/) if needed
// 2. Compile the Alpha5_NMDA_CA1_oyr directory via mknrndll. For help, see:
//    MSWindows: https://www.neuron.yale.edu/neuron/static/docs/nmodl/mswin.html
//    MacOS: http://www.neuron.yale.edu/neuron/static/docs/nmodl/macos.html
// 3. Launch start_simulation.hoc.
// 4. To change between the different simulations (i.e. Fig.8, Fig.S8 and S9), 
//    uncomment the respective hoc file in start_simultation.hoc 
//
////////////////////////////////////////////////////////////////////////////////