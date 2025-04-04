# <center><i>Kaggle Challenge</i></center>

# <center> Binary Prediction with Rainfall <a href="https://www.kaggle.com/competitions/playground-series-s5e3" target="_blank">[link]</a> </center>

## <center>Playground Series - Season 5, Episode 3 <center>

## Challenge Objective 🎯

The goal of the Tabular Playground Series is to provide the Kaggle community with a variety of fairly light-weight challenges that can be used to learn and sharpen skills in different aspects of machine learning and data science. The duration of each competition will generally only last a few weeks, and may have longer or shorter durations depending on the challenge. The challenges will generally use fairly light-weight datasets that are synthetically generated from real-world data, and will provide an opportunity to quickly iterate through various model and feature engineering ideas, create visualizations, etc.

---

## About the Dataset 📊

The dataset for this competition (both train and test) was generated from a deep learning model trained on the Rainfall Prediction using Machine Learning dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

- Download the dataset from here: [Kaggle Dataset](https://www.kaggle.com/competitions/playground-series-s5e3/data) 📥

## Dataset Features 📝

- **`id`**: just a serial number
- **`day`**: numeric day (i.e., 1,2,3)
- **`pressure`**: the atmospheric pressure
- **`maxtemp`**: maximum temperature
- **`temperature`**: average temperature
- **`mintemp`**: minimum temperature
- **`dewpoint`**: dewpoint 
- **`humidity`**: water vapour content in air.
- **`cloud`**: percentage of clouds in sky
- **`sunshine`**: amount of sunshine
- **`winddirection`**: direction of the wind
- **`windspeed`**: speed of the wind
- **`rainfall`**: will it rain or not.

<br>

## How to Set Up This Project 🛠️

This guide walks you through setting up the project's environment.

**1. Install Python 🐍**

If you don't have Python installed yet, head over to the official download page: [Python Download Guide](https://wiki.python.org/moin/BeginnersGuide/Download) and follow the instructions for your operating system (Windows, macOS, or Linux).

**<u>Optional: Creating a Virtual Environment 🌱</u>**

1. Create a virtual environment:

   In the terminal, run the following command:

   ```bash
   python -m venv venv
   ```

2. Activate the virtual environment:

   To activate the virtual environment, use:

   ```bash
   venv\Scripts\activate
   ```

**2. Download the Repo 📥**

1. Open your Git client or terminal.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command, replacing `<repository_url>` with the actual URL of the project's repository:

   ```bash
   git clone <repository_url>
   ```

**3. Install Required Dependencies 📦**

1. Open terminal/cmd.
2. Navigate to the repository directory.
3. Run the following command to install dependencies from `requirements.txt`:

   ```bash
   pip install -r ./backpack-prediction/requirements.txt
   ```