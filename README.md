# QNPack Tutorials

QNPack provides simulation tutorials for both **1G (memory-based) trapped-ion** and **All-Photonic (APE)** quantum repeater networks.  
All tutorials are implemented as **Jupyter Notebooks** and can be run directly inside **JupyterHub** or from a local source installation.

## Available Tutorials

### 1G Trapped-Ion Quantum Repeater Networks
- [**First 1G Simulation**](examples/1G_examples/1G_first.ipynb) – introductory simulation.  
- [**Parameters for 1G**](examples/1G_examples/1G_params.ipynb) – guide to selecting network parameters.  
- [**Scaling 1G Simulation**](examples/1G_examples/1G_scaling.ipynb) – demonstrates scaling to more repeater nodes. 
- [**1G Theoretical Rate Calculation**](examples/1G_examples/1G_theo_rate.ipynb) - for computing entanglement generation rate using analytic models.
- [**1G Theoretical Fidelity Calculation**](examples/1G_examples/1G_theo_fid.ipynb) – for computing end-to-end entanglement fidelity under different noise sources. 

### APE Quantum Repeater Networks
- [**First APE Simulation**](examples/APE_examples/APE_first.ipynb) - introductory simulation.

## Available Exercises
- [**1G_exercise.ipynb**](QCE25/1G_exercise.ipynb) – Practical notebook to explore 1G ion-trap quantum repeater concepts and protocols.  

### You can run either of the two repeater architectures:

- **1G Ion-Trap Repeater**  
  ```bash
  python qnpack/oneG/iontrap.py
  ```

- **APE Repeater**
  ```bash
  python qnpack/APE/allphotonic.py
  ```

