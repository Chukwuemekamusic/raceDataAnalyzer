# Race Data Analyzer

## Overview

Race Data Analyzer is a Python project designed to clean, standardize, and analyze race data, specifically focusing on ultramarathon events. Ultramarathons, also known as ultra distance or ultra running, are footraces longer than the traditional marathon length of 42.195 kilometers (26 miles 385 yards). This project extracts insights from race events, such as average speeds across different distances and seasons, with a particular focus on races held in the USA, including the 50 km and 50 mile distances.

The dataset includes a variety of ultramarathon distances, ranging from the shortest common ultramarathon of 31 miles (50 km) to over 200 miles (320 km). Both 50k and 100k are recognized as World Athletics record distances, and some 100-mile (160 km) races are among the oldest and most prestigious events, especially in North America. This project aims to provide valuable insights into these challenging and diverse races.

[link to the dataset used](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running)

## Features

- **Data Cleaning**: Standardizes race distances and formats event names.
- **Data Analysis**: Provides insights into race performance metrics, such as average speed by season and age group.
- **Data Export**: Saves cleaned data to a CSV file for further analysis or reporting.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/chukwuemekamusic/raceDataAnalyzer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd raceDataAnalyzer
   ```
3. Install the required dependencies:
   ```bash
   pip install pandas seaborn jupyter
   ```

## Usage

1. Run the Jupyter Notebook to clean and analyze the data:
   ```bash
   jupyter notebook data_cleaning_analysis.ipynb
   ```
2. The cleaned data will be saved to the `cleaned/cleaned_data_usa.csv` file.

## Project Structure

- `data_cleaning_analysis.ipynb`: Main notebook for data cleaning and analysis.
- `cleaned/`: Directory where the cleaned data is saved.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please contact [e.anyaegbunam@outlook.com](mailto:e.anyaegbunam@outlook.com).# Race Data Analyzer

