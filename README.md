# IMDb Movie Details Extractor
This project automates the process of extracting movie details from the IMDb Top 250 Movies list using UiPath. The workflow navigates to the IMDb website, retrieves the top movies based on user input, and saves the details (such as title, year, duration, and rating)
into a text file.
Workflow Overview
Open IMDb Website: The workflow opens the IMDb website in a Chrome browser.

Navigate to Top 250 Movies: It clicks on the menu and selects the "Top 250 Movies" option.

User Input: The user is prompted to enter the number of movies they want to retrieve.

Data Extraction: The workflow extracts the movie details from the webpage.

Data Processing: The extracted data is processed to separate the title, year, duration, and rating.

Save to File: The processed data is saved into a text file at the specified location.
# Example Output
The output text file will contain details in the following format:
1. The Shawshank Redemption
1994
2h 22m
9.3
--------------------------------------------
2. The Godfather
1972
2h 55m
9.2
--------------------------------------------
...
