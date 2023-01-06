# Fuzzy Database using Python and Pandas
This repository contains a Jupyter Notebook Python script that uses fuzzy logic to make recommendations for houses based on a CSV file of house listings. The script using Pandas as tool for data manipulation. The script prompts the user to create membership functions for each column of the CSV file (except the first one) and stores the resulting membership functions in a fuzzy database. The membership functions can be either triangular (TRIMF) or trapezoidal (TRAPMF). The script then asks the user to specify their preferences for each column and uses the membership functions to calculate a recommendation score for each house. The houses are then ranked and the top three recommendations are displayed to the user.
## Requirements
To use this script, you will need to have the following packages installed:
* Pandas
* Numpy
* Matplotlib
* Tkinter
## Usage
To use this script, follow these steps:
1. Place the "House.csv" file in the same directory as the script.
2. Run the script using a command prompt
3. Follow the prompts to enter information about the membership functions for each column.
4. Follow the prompts to specify your preferences for each column.
The script will plot the membership functions as they are created and display the top house recommendations based on your preferences.
## Notes
The script expects the CSV file to have a specific format with a specific set of column names. The included "House.csv" file is an example of a compatible file.
The script only handles two types of membership functions: TRIMF and TRAPMF.
The script expects the values for the membership function parameters to be entered in a specific order and to be floats.
