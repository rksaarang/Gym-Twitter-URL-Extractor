# Gym Twitter URL Extractor

This Python script fetches Twitter URLs for gyms listed in an Excel file. It utilizes multithreading to expedite the process of searching for Twitter handles associated with gym names and addresses.

## Script Overview

The script performs the following tasks:

- **Data Loading**: Loads gym information from an Excel file (`Data Science Batch Task Sheet.xlsx`).
- **Twitter URL Retrieval**: Searches for Twitter URLs associated with gym names and addresses using the Google search API.
- **Multithreading**: Utilizes threading to process gym information concurrently, enhancing efficiency.
- **Caching**: Stores and retrieves previously searched gym Twitter URLs from a cache (`twitter_cache`) to optimize search speed.

## Usage

1. **Input File**: Ensure the Excel file containing gym information (`Data Science Batch Task Sheet.xlsx`) is in the same directory as the script.
2. **Adjust Threads**: Modify the `num_threads` variable based on available system resources for concurrent processing.
3. **Run the Script**: Execute the script in a Jupyter Notebook or Python environment.

## Important Note

- **Resource Consideration**: Adjust the number of threads (`num_threads`) based on system resources to optimize performance without overwhelming the system.

## Output

The script saves the updated gym information with Twitter URLs to a new Excel file named `gyms_with_twitter_urls.xlsx`.

Feel free to explore and modify the script according to specific requirements or improvements.


