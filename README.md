# invisible-film

![](8V9H.gif)

This probject aims to find _invisible films_ — hidden gems from diverse cultures that are high quality but still largely unheard of — often because they are in a non-mainstream language or set in a non-Eurocentric context or made with less resources. 

We build on data from https://www.themoviedb.org/ for these analyses. Access to cleaned data can be requested by emailing [Saurabh Khanna](mailto:s.khanna@uva.nl).

**Codebook of Current Data**

| Column Name           | Data Type   | Description   |
|:----------------------|:------------|:--------------|
| adult                 | bool        | Whether the movie is marked as adult content (True/False). |
| backdrop_path         | object      | URL path to the movie’s backdrop image. |
| belongs_to_collection | object      | Collection that this movie belongs to, if any. |
| budget                | int64       | Budget of the movie in US dollars. |
| genres                | object      | List of genres associated with the movie. |
| homepage              | object      | Official website URL of the movie, if available. |
| id                    | int64       | Unique TMDb movie ID. |
| imdb_id               | object      | IMDb identifier for the movie (e.g., "tt1517268"). |
| origin_country        | object      | List of country codes where the movie was produced. |
| original_language     | object      | The original language of the movie (e.g., "en" for English). |
| original_title        | object      | The movie's original title. |
| overview              | object      | A brief plot summary of the movie. |
| popularity            | float64     | Popularity score based on TMDb's internal metrics. |
| poster_path           | object      | URL path to the movie’s poster image. |
| production_companies  | object      | List of production companies involved in the movie. |
| production_countries  | object      | List of countries where the movie was produced. |
| release_date          | object      | The official release date of the movie (YYYY-MM-DD). |
| revenue               | int64       | Total revenue of the movie in US dollars. |
| runtime               | int64       | Duration of the movie in minutes. |
| spoken_languages      | object      | List of languages spoken in the movie. |
| status                | object      | Release status of the movie (e.g., "Released", "Post Production"). |
| tagline               | object      | The movie’s promotional tagline. |
| title                 | object      | The title of the movie. |
| video                 | bool        | Whether a video is associated with this record (True/False). |
| vote_average          | float64     | Average rating of the movie on TMDb. |
| vote_count            | int64       | Number of votes cast for the movie on TMDb. |
