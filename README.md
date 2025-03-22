# Top Expensive Leagues Data Cleaning & Analysis

## Overview
This project focuses on cleaning and analyzing a dataset of the world's most expensive sports leagues. The SQL script performs data preprocessing, standardization, and ranking to derive key insights into league revenue, salaries, and viewership.

## Features
- **Data Cleaning**:
  - Removes duplicate league records.
  - Handles missing values in revenue, salaries, and viewership.
- **Data Standardization**:
  - Optimizes data types for efficient storage and querying.
  - Normalizes country names to maintain consistency.
- **Outlier Detection**:
  - Identifies and handles extreme values in revenue data.
- **Derived Metrics**:
  - Calculates `Revenue per Team` and `Salary as % of Revenue`.
- **Ranking & Insights**:
  - Assigns ranks to leagues based on revenue and viewership.
  - Creates a SQL view (`top_leagues`) for the top-performing leagues.

## Requirements
- MySQL / PostgreSQL (or any SQL-supported database)
- SQL-compatible query execution environment

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/top-expensive-leagues.git
   ```
2. Import the dataset into your database.
3. Run the SQL script to clean and analyze the data.
4. Query the `top_leagues` view to extract insights.

## Example Query
```sql
SELECT * FROM top_leagues;
```

## Contributing
Feel free to fork this repository and contribute improvements via pull requests.

## License
This project is open-source under the MIT License.

