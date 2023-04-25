# Music Dataset Explored using PySpark.


This repository contains a Python script that uses Apache Spark to analyze a dataset of music listenings. The code performs several queries on the data to extract insights about users, artists, tracks, genres, and albums. The script also uses matplotlib to visualize some of the results.

## Prerequisites

To run the script, you need to have the following software installed on your machine:

- Python 3.x
- Apache Spark
- matplotlib

You also need to have the dataset files `listenings.csv` and `genre.csv` available in a local or remote folder. The script assumes that the files are in the same format as the ones provided in the `dataset` folder of this repository.

## Usage

To use the script, follow these steps:

1. Clone this repository to your local machine.
2. Open a terminal or command prompt and navigate to the repository folder.
3. Run the command `pip install pyspark` to install the PySpark module.
4. Edit the `main.py` file to set the paths to the dataset files and adjust any other parameters as needed.
5. Run the command `python main.py` to execute the script.
6. Wait for the script to finish running. The results will be printed to the console and some of them will be plotted using matplotlib.

## Results

The script produces the following results:

- Query #0: select the artist and track columns of the listenings dataset.
- Query #1: select all the listenings records of the users who have listened to Rihanna.
- Query #2: find the top 10 users who are fans of Rihanna.
- Query #3: find the top 10 famous tracks of all artists.
- Query #4: find the top 10 famous tracks of Rihanna.
- Query #5: find the top 10 famous albums of all artists.
- Query #6: find the top 10 users who are fans of pop music.
- Query #7: find the top 10 famous genres of all artists.
- Query #8: find out each user's favorite genre of music.
- Query #9: count the number of artists in the pop, rock, metal, and hip hop genres, and plot the results using a bar chart.

The results are printed to the console in tabular format, and some of them are also plotted using matplotlib.


Best Of Luck,

Aayush Doshi
