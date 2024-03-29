<div align="center">
    <h1>Book recommendation system</h1>
</div>

## Build book recommendation system based on Collaborative Filtering

### Introduction
The interface of the project has the top 20 books in the dataset, while the recommendation page suggests four books after the user enters the title of a book.

### Repository Structure
* **README.md**: The top-level README for reviewers of this project
* **requirements.txt**: requirements file; including the needed tools
* **notebooks**: `01.data_exploration.ipynb` is for exploring the dataset. `02.recommendation_system.ipynb` is for building our recommendation program.
* **pkl_file**: pkl files from `02.recommendation_system.ipynb`
* **static**: 
    - **data folder**: has the datasets.
    - **img folder**: has the images used in README.md.
* **templates folder**: This folder for html files.
* **app.py**: Flask application to give the recommendations
* **Procfile**: .

### Libraries
* pandas
* NumPy
* flask


### Algorithm
Collaborative Filtering Based Recommender System

## Getting the app running localy
1. Colone this repo
```
git clone https://github.com/khalidsbn/books-recommendation.git
```
2. Create and activate a virtual environment
```
python3 -m venv .venv
source .venv/bin/activate
```
3. Install the required dependencies (pandas, Numpy, etc)
```
pip install -r requirements.txt
```
4. Run app.py


Running the above command should result in you seeing the following:

<img src="static/img/interface_page.png" width="800"/>

This page has the most 20 popular books.

5. Try to enter the name of a book

<img src="static/img/recommendation_page.png" width="800"/>

6. Click show to get the recommendations
<img src="static/img/recommendation.png" width="800"/>
