# moravec-transfer-sandbox

# Cybernetic Engram Shunt: Simulated Moravec Transfer Sandbox

An end-to-end Python implementation demonstrating the theoretical mechanics of a **Moravec Transfer** (Ship of Theseus mind uploading) using a Spiking Neural Network (SNN) sandbox.

This project simulates a small biological cortical network using computationally efficient **Izhikevich Spiking Neurons**, forcefully embeds a silent structural memory engram, extracts it using an artificial Sharp-Wave Ripple (SWR) protocol, transfers it to a digital silicon Exocortex via STDP learning, and writes it back to the host tissue.

---

## Architecture Pipeline

### Phase 1: Biological Wetware Simulation & Background Noise
* Initializes a 100-neuron network (80% excitatory, 20% inhibitory) using the Izhikevich model to simulate regular-spiking cortical dynamics.
* Injecting a latent, structural "Silent Memory" by manually hardening a sequential synaptic pathway (Neuron 10 → 11 → ... → 20).
* Introduces continuous Poisson-like background current noise to mimic live organic brain environments.

### Phase 2 & 3: The Ping-and-Record Protocol (SWR Trigger)
* Simulates an artificial Sharp-Wave Ripple by delivering a high-amplitude current pulse to the anchor node (Neuron 10).
* Records the resulting millisecond-precise electrical cascade as it races down the pre-configured structural blueprint.
* Isolates the true sequence out of the chaotic baseline noise.

### Phase 4: The Cybernetic Transfer (STDP Assimilation)
* Feeds the isolated biological tensor into a clean, unconfigured **Artificial Exocortex**.
* Executes **Spike-Timing-Dependent Plasticity (STDP)** rules: when a presynaptic digital node fires right before a postsynaptic node, the silicon synapse permanently fortifies its mathematical weight, capturing the biological ghost.

### Phase 5: Biomimetic Hardware Write-Back (Closing the Loop)
* Translates the finalized Exocortex synaptic matrix back into a time-delimited series of microsecond-precise voltage commands.
* Fires the sequence back into the biological array, demonstrating a closed-loop cybernetic shunt capable of driving organic thought patterns on command.

---

## Repository Contents
* `mimo_total_simulation.ipynb` - The complete self-contained Jupyter Notebook containing all 5 phases of the simulation, network configurations, and plotting routines.

## Prerequisites & Installation

To run this simulation, you need a standard Python 3 environment with `numpy` and `matplotlib` installed.

```bash
pip install numpy matplotlib
```

## How to Run

1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/moravec-transfer-sandbox.git](https://github.com/YOUR_USERNAME/moravec-transfer-sandbox.git)
   ```
2. Open the notebook in your preferred environment (Jupyter Lab, VS Code, or Google Colab):
   ```bash
   jupyter notebook mimo_total_simulation.ipynb
   ```
3. Run all cells sequentially.

## Expected Outputs

Upon running the execution cells, the script will spin up a dual-plot `matplotlib` visualization:
1. **The Raster Plot:** Displays the raw spike timings of all 100 neurons over 1000ms, making the breakthrough memory cascade visually distinct from the salt-and-pepper background noise.
2. **The Voltage Trace:** Pinpoints the membrane potential of the specific target neurons, tracking their climb to threshold during the cybernetic write-back.

The console will also output the precise microsecond-to-millisecond latency logs verifying if the cybernetic transfer executed within the biological synaptic threshold (<2.0 ms).

---
*Disclaimer: This repository serves as a closed-loop mathematical sandbox proving the software architecture required for real-time memory digitization and restoration.*
