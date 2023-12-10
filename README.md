# data-sourcing-challenge
Module 6 Challenge

# NYT and TMDB Movie Reviews

## Overview
This Python script is designed to retrieve movie reviews from The New York Times (NYT) API, extract relevant information, and complement the dataset by querying The Movie Database (TMDB) API for additional movie details. The collected data is then merged, cleaned, and exported to a CSV file for comprehensive analysis.

## Dependencies
Make sure you have the required Python libraries installed. You can do this by running the following command:

```bash
pip install requests time python-dotenv pandas
```

Moreover, you need to obtain API keys for both NYT and TMDB. Place these keys in a file named `example.env` using the following format:

```env
NYT_API_KEY=your_nyt_api_key
TMDB_API_KEY=your_tmdb_api_key
```

## Usage
Follow these steps to utilize the script effectively:

1. Clone the repository to your local machine.
2. Install the necessary Python libraries.
3. Obtain API keys for NYT and TMDB and set them in the `example.env` file.
4. Run the script using the command:
    ```bash
    python script_name.py
    ```
5. The script will fetch movie reviews from NYT, query TMDB for supplementary details, merge the datasets, clean the data, and finally export it to a CSV file named `NYT_and_TMDB_merged_reviews.csv`.

## Note
To comply with API query limits, the script introduces delays between requests. Ensure your API keys are valid and have the required permissions.

Feel free to reach out for any clarifications or assistance!

Written by ChatGPT
