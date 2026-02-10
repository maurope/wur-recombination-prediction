WUR Recombination Prediction Repository
=============

* Written by: Mauricio Peñuela\
* Last update: 02/10/26



📘 Overview
------

This repository contains **dataframes**, **code**, **results**, and **figures** for data exploration, model training, and validation related to the **recombination prediction project** from the *Genome Biology Unit*, Graduate School of Experimental Plant Sciences, **Wageningen University**.



🧬 Data Description
------

The datasets and analyses cover:

- **Interspecific recombinant populations** of *Brassica oleracea*
- An **interspecific dataset** of tomato (*Solanum lycopersicum × S. pimpinellifolium* cross)

Folder names reflect the type of training features used in each analysis:


- **k-mers**: k-mers length 3

- **expression**: expression elements

- **repetitive**: repetitive elements

- **all**: all feature types combined

Each subfolder contains results and models corresponding to the respective input features.



🚀 Setup
------

Clone the repository::

  git clone git@github.com:maurope/wur-recombination-prediction.git


📁 Requirements
------

Install all of the modules listed in the Python requirements file into the project environment::

  pip install -r requirements.txt


📌 Notes
------

- All analyses are conducted in Python using Jupyter Notebooks.
- Make sure to use an updated Python version (3.9+ recommended).



📄 License
------

This project is open access and intended for academic and research purposes.  
You may freely use and adapt the materials, provided appropriate attribution is given.

For questions or collaborative opportunities, feel free to reach out to the author.

📄 Publications
------

`Penuela, M. Bonnema, G. Auxier, B. Bouwmeester, K. van Peer, A. Schouten, H. Peters, S. van Dijk, A. D. J. Bai, Y. de Ridder, D. 2026 .Genome-based prediction of recombination within and between plant species: insights
from Brassica oleracea recombinant populations and an interspecific tomato cross (Solanum lycopersicum × S. pimpinellifolium). BMC Plant Biology <https://link.springer.com/article/10.1186/s12870-025-07922-8>`_




