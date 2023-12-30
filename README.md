# Red Wine Predication Machine Learning End to End Project 

## Table of Contents

- [Business Understanding](#BusinessUnderstanding)
- [File Structure](#file-structure)
- [Installation](#installation)


## Business Understanding

![](https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/delicious-red-wine-royalty-free-image-1585590768.jpg?resize=768:*)

The red wine industry shows a recent exponential growth as social drinking is on the rise. Nowadays, industry players are using product quality certifications to promote their products. `This is a time-consuming process and requires the assessment given by human experts, which makes this process very expensive`. Also, the price of red wine depends on a rather abstract concept of wine appreciation by wine tasters, opinion among whom may have a high degree of variability. Another vital factor in red wine certification and quality assessment is `physicochemical tests, which are laboratory-based and consider factors like acidity, pH level, sugar, and other chemical properties.` The red wine market would be of interest if the human quality of tasting can be related to wine’s chemical properties so that certification and quality assessment and assurance processes are more controlled. `This project aims to determine which features are the best quality red wine indicators and generate insights into each of these factors to our model’s red wine quality.` 

## File Structure


- `/src`: Source code directory.
  - `YourProjectName`: Your project name as a subdirectory.
    - `/components`: Components module.
    - `/utils`: Utilities module.
      - `common.py`: Common utility functions.
    - `/config`: Configuration module.
      - `configuration.py`: Configuration settings.
    - `/pipeline`: Pipeline module.
    - `/entity`: Entity module.
      - `config_entity.py`: Configuration entity.
    - `/constants`: Constants module.
- `/config`: Configuration files.
- `/main.py`: Main Python script.
- `/app.py`: App Python script.
- `/requirements.txt`: Requirements file.
- `/setup.py`: Setup file.
- `/research`: Research directory.
  - `trials.ipynb`: Jupyter notebook for research.
- `/templates`: HTML templates.
- `/params.yaml`: Parameters file.
- `/schema.yaml`: Schema file.


## Installation

```bash
conda create -p env python=3.8 -y 
```
```bash
conda activate env  
```

```bash
pip install -r requirements.txt
```

