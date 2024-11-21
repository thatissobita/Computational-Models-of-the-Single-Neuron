# Computational Models of the Single Neuron

Welcome to the **Computational Models of the Single Neuron** repository! This project explores the implementation and analysis of single neuron spiking models using the `pymonntorch` framework. It includes models like Leaky Integrate-and-Fire (LIF), Exponential Leaky Integrate-and-Fire (ELIF), Adaptive Exponential Leaky Integrate-and-Fire (AELIF), and Refractory ELIF.  

## Features  
- **Comprehensive analysis:** Covers LIF, ELIF, AELIF, and Refractory ELIF models.  
- **Interactive notebook:** A single Jupyter notebook (`Single-Neuron-Model.ipynb`) contains the implementation, simulation, and visualization of all models.  
- **Visualization resources:** Pre-generated plots and figures included in the `resources/` folder.  
- **Detailed report:** A well-documented `report.pdf` provides the theoretical background, results, and insights.  

---

## Installation  

1. Clone this repository:  
   ```bash
   git clone https://github.com/thatissobita/Single-Neuron-Model.git
   cd Single-Neuron-Model
   ```  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

   **Note:** Ensure you have Python 3.8 or higher installed.  

---

## Usage  

### Running the Jupyter Notebook  

1. Open the Jupyter notebook:  
   ```bash
   jupyter notebook Computational-Models-of-the-Single-Neuron.ipynb
   ```  

2. Follow the step-by-step implementation for each model.  
3. Generate plots and analyze the results directly within the notebook.  

---

## Directory Structure  

```plaintext  
Single-Neuron-Model/  
│  
├── Single-Neuron-Model.ipynb      # Jupyter notebook containing implementation and analysis of all models  
│  
├── report.pdf                     # Detailed report including results and analysis  
│  
├── resources/                     # Folder for visualization resources  
│   ├── plot_lif                   # Visualization of LIF model  
│   ├── plot_elif                  # Visualization of ELIF model  
│   ├── plot_aelif                 # Visualization of AELIF model  
│  
├── requirements.txt               # Python dependencies  
├── LICENSE                        # License information  
├── README.md                      # Project documentation  
└── .gitignore                     # Git ignored files  
```  

---

## Results  

The `resources/` folder contains pre-generated plots, including:  
- Voltage traces for each neuron model.  
- Spike raster plots.  
- Comparative parameter analysis.  

Refer to the `report.pdf` for a detailed discussion of these results.  

---

## Dependencies  

- Python 3.8+
- `pytorch`
- `pymonntorch`  
- `numpy`  
- `matplotlib` 

Install all dependencies using the provided `requirements.txt` file.  

---

## Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a feature branch.  
3. Submit a pull request with your changes.  

For major changes, please open an issue to discuss your ideas.  

---

## Acknowledgements  

This project leverages the [pymonntorch](https://github.com/cnrl/PymoNNtorch) framework for spiking neural network simulations.  

Happy learning and experimenting!
