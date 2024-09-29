# Netflix Movies and TVShows Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Key Insights](#key-insights)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project aims to analyze and provide recommendations for a movie streaming platform using a dataset of Netflix movies and TV shows. By examining various attributes such as ratings, genres, and release years, the project aims to derive valuable insights and build a simple recommendation system.

## Dataset
The dataset used in this project is the **Netflix Movies and TV Shows** dataset, which contains the following columns:
- `show_id`: Unique identifier for each show
- `type`: Indicates whether the entry is a movie or a TV show
- `title`: Title of the show
- `cast`: List of actors
- `country`: Country where the content was produced
- `date_added`: Date when the content was added to the platform
- `release_year`: Year the content was released
- `rating`: Content rating (e.g., PG, R)
- `duration`: Duration of the movie (in minutes) or number of seasons for TV shows
- `listed_in`: Genres and categories of the show
- `description`: Brief description of the show

## Technologies Used
- **Google Cloud Platform**: BigQuery for data storage and SQL queries
- **Python**: For data cleaning and analysis (using libraries like Pandas)
- **Google Colab**: For running Python code and cleaning the dataset
- **SQL**: For querying and analyzing data in BigQuery

## Key Insights
- Count of movies and shows by type
- Average duration of movies and shows
- Distribution of ratings among different genres
- Top-rated genres
- Recommendation system based on user preferences

## Usage
1. Upload the cleaned dataset to Google BigQuery.
2. Execute SQL queries to gain insights and analyze the data.
3. Utilize the insights to build a simple recommendation system based on user preferences.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

