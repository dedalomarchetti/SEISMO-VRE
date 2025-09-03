# SEISMO-VRE
This is a Virtual Research Environment (VRE) in the form of Jupyter Notebook with MATLAB or Python kernel dedicated to a multiparametric and multidisciplinary study of an earthquake.  
It integrates geophysical, atmospheric, and solar datasets to support interdisciplinary research.
The first developed version is the one with the MATLAB kernel, so for eventual differences, this is the reference VRE.

## Requirements 
### for MATLAB Version 

- [Jupyter Notebook](https://jupyter.org/) or [JupyterLab](https://jupyter.org/)
- MATLAB with the [MATLAB kernel for Jupyter](https://github.com/Calysto/matlab_kernel)
- MATLAB Toolboxes: 'Mapping', 'Statistics and Machine Learning' and 'Curve Fitting'
- (Optional) Python environment via Anaconda or similar
### for Python version
- see the specific file `requirements.txt`

## How to Run (*)

1. Clone the repository:
   ```bash
   git clone https://github.com/dedalomarchetti/SEISMO-VRE.git
   cd SEISMO-VRE
   ```

2. Start Jupyter:
   ```bash
   jupyter notebook
   ```

3. For MATLAB version, please open `SEISMO-VRE_MATLAB_v1.0.ipynb` and follow the instructions inside.  
   For the Python version, please open `SEISMO-VRE_Python_v1.0.ipynb` instead.

\* If you want to just view the Notebook you can simply click inside GitHub on the file `VRE_Amatrice_v1.5.ipynb` to preview it inside the same GitHub.

## Repository layout

| File                              | Description                                                                            |
| ----------------------------------| ---------------------------------------------------------------------------------------|
| **`SEISMO-VRE_Matlab_v1.0.ipynb`**| Virtual Research Environment (VRE) in the form of Jupyter Notebook with MATLAB kernel  |
| **`SEISMO-VRE_Python_v1.0.ipynb`** | Virtual Research Environment (VRE) in the form of Jupyter Notebook with Python kernel |
| **`requirements.txt`**            | Strict dependency pinning for reproducible Python environments                         |
| **`data folder`**                 | Atmospheric and geomagnetic data                                                       |
| **`extra_code folder`**           | Additional functions for Matlab VRE                                                    |
| **`publications folder`**         | Conference abstract and proceedings                                                    |
| **`LICENSE`**                     | GPL 3.0 licence text.                                                                  |

---
## Scientific contribution

This work has been presented at the GNGTS 2025 conference (Bologna, Italy, 11 February 2025) with a poster titled:
"An inter-disciplinary Virtual Research Environment to study the Amatrice-Norcia Italian seismic sequence 2016"
It will be presented at EGU 2025 (Vienna, Austria, 2 May 2025) with a virtual poster titled:
"A Jupyter Notebook devoted to a multiparametric investigation of the Amatrice-Norcia Italian seismic sequence 2016-2017"
and at ICCSA 2025 under the title:
"A multiparametric investigation of an earthquake by a Jupyter Notebook: the case study of the Amatrice-Norcia Italian seismic sequence 2016-2017"

## Collaborators
The collaborators of this work are:

Dedalo Marchetti (1), Daniele Bailo (1), Giuseppe Falcone (1), Jan Michalek (2), Rossana Paciello (1), Alessandro Piscini (1)

1. Istituto Nazionale di Geofisica e Vulcanologia (INGV), Italy  
2. University of Bergen, Norway

## License

This project is licensed under the GPL 3.0 License. See the [LICENSE](LICENSE) file for details.

## Contributing

1. **Fork** the repository.
2. Create a feature branch: `git checkout -b feature/my‑idea`.
3. **Commit** your changes: `git commit -am 'Add awesome feature'`.
4. **Push** the branch: `git push origin feature/my‑idea`.
5. Open a **Pull Request** and describe your improvement.

All contributions — bug reports, feature ideas, documentation — are welcome! 🙌

## How to Cite
If you use SEISMO-VRE in your research, please cite it as follows:

Marchetti, D., Bailo, D., Falcone, G., Michalek, J., Paciello, R., & Piscini, A. (2023). SEISMO_VRE. GitHub. https://github.com/dedalomarchetti/SEISMO-VRE

DOI: https://doi.org/10.5281/zenodo.1234567 (Sostituisci con il tuo DOI corretto)

BibTeX
If you are using BibTeX, you can use the following entry:  
@software{marchetti_2023_seismo_vre,  
author       = {Marchetti, Dedalo and  
Bailo, Daniele and  
Falcone, Giuseppe and  
Michalek, Jan and  
Paciello, Rossana and  
Piscini, Alessandro},  
title        = {{SEISMO_VRE}},  
url          = {https://github.com/dedalomarchetti/SEISMO-VRE},  
version      = {v1.0.0},  
date         = {2023-10-27},  
}
