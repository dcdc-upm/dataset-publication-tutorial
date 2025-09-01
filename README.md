# Dataset Publication Tutorial  
This repository contains a **tutorial on dataset publication following best practices for documentation, metadata, and reproducibility**.  

As a case study, we reused the dataset [Traffic Accidents in the City of Madrid](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=7c2843010d9c3610VgnVCM2000001f4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default), published by the **City Council of Madrid**, specifically using the records for the year **2024**.  

From this resource, we created a derived dataset: **Fatal Traffic Accidents in the City of Madrid (2024)**, obtained by filtering all accidents that did not result in at least one fatality.  

The tutorial, available in the `src` folder, provides a hands-on guide on how to:  
- Document a repository content according to standards and **FAIR principles** (Findable, Accessible, Interoperable, Reusable).  
- Publish the dataset in open digital repositories.  

Supporting documentation is provided in the `docs` folder and should be reviewed before running the scripts.  

The transformed dataset has been published on two platforms as a didactic example (⚠️ *publishing the same dataset in multiple repositories is generally not recommended in real-world practice, but is done here for educational purposes*):  
- [Zenodo](https://doi.org/10.5281/zenodo.17018859)  
- [Hugging Face](https://huggingface.co/datasets/iguillenp/Fatal_traffic_accidents_in_the_city_of_Madrid_during_2024_Dataset_Publication_Tutorial)  

## Prerequisites  
To execute the tutorial you will need:  
- **Python 3.13.5**  
- Install the conda environment defined in `environment.yml`:  

```bash
conda env create -f environment.yml
```

## License
Este repositorio y todo el material que contiene está bajo la licencia CC BY-NC 4.0, para más información consultar el archivo LICENSE.  However, the dataset is distributed under the license terms of the [City of Madrid Open Data Portal](https://datos.madrid.es/egob/catalogo/aviso-legal).

## License  
This tutorial repository (code, documentation, instructions) is governed by [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) license.  

However, both the original dataset and the transformed dataset of the fatal Traffic Accidents in Madrid 2024 are distributed under the license terms of the [City of Madrid Open Data Portal](https://datos.madrid.es/egob/catalogo/aviso-legal).

Please make sure to comply with both licenses when reusing the materials.  
