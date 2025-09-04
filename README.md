# Dataset Publication Tutorial

This repository contains a **tutorial on dataset publication following best practices for documentation, metadata, and reproducibility**. As a case study, we reused the dataset [Traffic Accidents in the City of Madrid](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=7c2843010d9c3610VgnVCM2000001f4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default), published by the **City Council of Madrid**, specifically using the records for the year **2024**.  

From this resource, we created a derived dataset: **Fatal Traffic Accidents in the City of Madrid (2024)**, obtained by filtering all accidents that did not result in at least one fatality. The transformed dataset has been published on three platforms as a didactic example:  
- [Zenodo](https://doi.org/10.5281/zenodo.17054802)  
- [Hugging Face](https://huggingface.co/datasets/iguillenp/fatal_traffic_accidents_in_the_city_of_madrid_2024)
- [Kaggle](https://www.kaggle.com/datasets/ibaiguillenpacho/fatal-traffic-accidents-in-the-city-of-madrid-2024/)

> [!WARNING]
> Publishing the same dataset in multiple repositories is generally not recommended in real-world practice, but is done here for educational purposes.
---

## 📖 Tutorial Overview  

The main tutorial is provided in the Jupyter notebook [`src/Tutorial.ipynb`](src/Tutorial.ipynb).  
It offers a **hands-on guide** on how to:  
- Document a dataset according to standards and the **FAIR principles** (Findable, Accessible, Interoperable, Reusable).  
- Publish the dataset in open digital repositories.  

> [!NOTE]  
> Before running the tutorial in the `src` folder, please review the supporting documentation in the [`docs`](./docs) folder.  

---

## ⚙️ Prerequisites  
To execute the [tutorial](src/Tutorial.ipynb) notebook you will need:  
- **Python 3.13.5**  
- Install the conda environment defined in `environment.yml`:  
```bash
conda env create -f environment.yml
```
- Configure this environment as a Jupyter kernel.
- Open and run the notebook

---

## 📜 License  

This repository (code, documentation, and instructions) is licensed under:  
- [Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)  

Datasets included in this tutorial are licensed separately:  
- **Original dataset**: subject to the terms of the [City of Madrid Open Data Portal](https://datos.madrid.es/egob/catalogo/aviso-legal).  
- **Derived dataset (Fatal Traffic Accidents 2024)**: redistributed under the same terms. 
