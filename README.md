## Dataset Setup

The datasets for this project are hosted externally. They will be automatically downloaded when the notebooks are run.

### Dataset Files:
1. `raw_data.csv` (Google Drive Link: [Click Here](https://drive.google.com/file/d/1_e9Q4-ymjHYNFJzVwbVXXPrYI33786oW/view?usp=drive_link))
2. `cleaned_data.csv` (Google Drive Link: [Click Here](https://drive.google.com/file/d/1Sdg9CJKbpmccciLWTvnFv3FCKCrywyls/view?usp=drive_link))
3. `text_preprocessed_scaled.csv` (Google Drive Link: [Click Here](https://drive.google.com/file/d/1ATmJvIc9EsDkE8agxqbE27-gIWjwVb5i/view?usp=drive_link))


## Create data folder if required in the project directory

##this is my project structure

fake-news-detection/
|
├──data/      #the datasets made pubic in the google drive are linked to download the datasets and after loading they must be saved as .csv files in this directory
|  ├──raw/
|  ├──processed/
|
├──notebooks/
|  ├──eda.ipynb
|  ├──text_preprocessing.ipynb
|  ├──model_training.ipynb
|
├──src/
├── requirements.txt       # Required Python libraries
├── README.md              # Project documentation
├── .gitignore 
