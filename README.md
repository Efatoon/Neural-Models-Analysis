# Neural Models Analysis

---

## Project Overview

This project implements and analyzes computational neuroscience models to simulate realistic neural behavior at both the single neuron and network levels. Using the FitzHugh–Nagumo and Izhikevich neuron models, it explores neuronal firing patterns, network synchronization, and complex neural dynamics through mathematical modeling and visualization.

Key objectives include:  
- Simulating individual neuron dynamics and their response to stimuli  
- Modeling and analyzing neural network behavior  
- Comparing different neuron models in terms of biological realism and computational efficiency  
- Visualizing spiking activity, phase plane dynamics, and network connectivity  

---

## Models Implemented

### 1. FitzHugh–Nagumo Model  
A simplified model of neural excitability capturing essential dynamics using coupled differential equations.  
- Exhibits threshold-based firing behavior  
- Shows stable oscillations and limit cycles  
- Useful for studying subthreshold and spiking dynamics  

### 2. Izhikevich Neuron Model  
A computationally efficient yet biologically plausible model with spike-reset mechanisms.  
- Produces realistic spike waveforms and firing patterns  
- Captures refractory periods and bursting behavior  
- Suitable for large-scale network simulations  

---

## Network Simulation

- Mixed population of excitatory and inhibitory neurons (80% excitatory, 20% inhibitory)  
- Directed, densely connected network topology  
- Emergent synchronization and structured population activity observed  
- Metrics such as firing rates, interspike intervals, and synchronization indices are analyzed  

---

## Key Results

- Both models replicate fundamental neural properties, including threshold dynamics and refractory periods  
- The Izhikevich model provides sharper spikes and faster dynamics with greater computational efficiency  
- Network simulations reveal complex temporal patterns and biologically realistic firing statistics  
- Stable and scalable simulations supporting up to 1000 neurons in real-time  

---

## Installation

```
git clone https://github.com/yourusername/neural-models-analysis.git
cd neural-models-analysis
pip install -r requirements.txt
```

## Future Work
- Implement synaptic plasticity and learning rules
- Explore more complex network architectures and connectivity patterns
- Integrate additional neuron models for broader comparisons
- Develop interactive visualization tools for dynamic analysis

## References
- FitzHugh, R. (1961). Impulses and physiological states in theoretical models of nerve membrane. Biophysical Journal, 1(6), 445–466.
- Izhikevich, E. M. (2003). Simple model of spiking neurons. IEEE Transactions on Neural Networks, 14(6), 1569–1572.

