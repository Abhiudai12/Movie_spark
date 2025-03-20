# Movie Recommendation System using Apache Spark

## Overview
This project is a Movie Recommendation System built using Apache Spark, leveraging collaborative filtering techniques to suggest movies based on user preferences.

## Features
- Uses Apache Spark for scalable data processing.
- Implements collaborative filtering with ALS (Alternating Least Squares) algorithm.
- Processes large movie datasets efficiently.
- Provides personalized movie recommendations.

## Technologies Used
- **Apache Spark** for distributed computing
- **Python (PySpark)** for data processing
- **MovieLens Dataset** for training and evaluation

## Installation
### Prerequisites
- Install Java (required for Spark)
- Install Apache Spark
- Install Python and required dependencies

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/movie-recommender-spark.git
   cd movie-recommender-spark
   ```
2. Install dependencies:
   ```sh
   pip install pyspark
   ```
3. Run the application:
   ```sh
   python main.py
   ```

## Dataset
The dataset is uploaded with this repo.

## Usage
1. Load the dataset into Spark.
2. Train the ALS model using user-movie rating data.
3. Generate movie recommendations for users.
4. Display recommendations.

## Example Output
```
Top 5 movie recommendations for User 123:
1. The Godfather (1972)
2. Pulp Fiction (1994)
3. Inception (2010)
4. The Shawshank Redemption (1994)
5. The Dark Knight (2008)
```

## Deployment
- The system can be deployed on local Spark clusters or cloud environments like AWS EMR or Databricks.

## License
This project is licensed under the MIT License.
