# Code Review: Team Week

#### By Ruben Giosa, Alejandro Socarras, Drew White

#### This repo includes exercises for working with datasets using pandas working as a team. 

<br>

## Technologies Used

* Python
* Pandas
* GeoPandas
* Pyplot
* Matplot
* Folium
* Git
* Markdown
* JSON
* NumPy
* `.gitignore`
* `requirements.txt`

</br>

## Datasets Used

1. [USA Real Estate Data](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)
2. [Global Cost of Living](https://www.kaggle.com/datasets/mvieira101/global-cost-of-living)
3. [World Happiness Report 2021](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021)
4. [Global Quality of Life](https://www.kaggle.com/datasets/cityapiio/countries-quality-of-life-index-2020-year)

</br>

## Description

This repo includes data manipulation for datasets working with a team. Alejandro performed profiling, cleaning and transformations on the Cost of Living data, and exported to a clean version of the csv named `cost_living.csv`. Drew worked on profiling, cleaning and transformations for the World Happiness and Global Quality of Life data sets to merge into `world_happiness_clean.csv`. Ruben performed profiling, cleaning and transformations on the Realtor data (`clean_realtor_data.csv`), and then joined the other contributors' datasets into one consolidated csv file. The realtor and cost of living data were concatenated in order to expand the data set for price per square meter data at the city level. Then that expanded data (`cost_living_with_realtor.csv`) set was merged with `world_happiness_clean.csv` into the consolidated `cl_real_happiness.csv`.

Once the datasets were cleaned and consolidated, the team created (and in some cases recreated) data visualizations and analysis using `cl_real_happiness.csv`. In the `rg_maps.ipynb` notebook is a geo heat map of life expectancy by country that was put together by Ruben. 

<br>

## Setup/Installation Requirements

* Go to https://github.com/apsocarras/team-week.git to find the specific repository for this website.
* Then open your terminal. I recommend going to your Desktop directory:
    ```bash
    cd Desktop
    ```
* Then clone the repository by inputting: 
  ```bash
  git clone https://github.com/apsocarras/team-week.git
  ```
* Go to the new directory or open the directory folder on your desktop:
  ```bash
  cd python-adv-cr
  ```
* Once in the directory you will need to set up a virtual environment in your terminal:
  ```bash
  python3.7 -m venv venv
  ```
* Then activate the environment:
  ```bash
  source venv/bin/activate
  ```
* Install the necessary items with requirements.txt:
  ```bash
    pip install -r requirements.txt
  ```
* With your virtual environment now enabled with proper requirements, open the directory:
  ```bash
  code .
  ```

</br>

## Known Bugs

* No known bugs

<br>

## License

MIT License

Copyright (c) 2022 Ruben Giosa, Alejandro Socarras, Drew White

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

</br>
