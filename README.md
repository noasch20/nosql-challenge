# UK Food Standards Agency Database Analysis

This project analyzes food hygiene ratings of UK establishments from the Food Standards Agency (FSA) to help **Eat Safe, Love** magazine focus on the best places for future articles.

## Part 1: Database Setup
- Imported data from `establishments.json` into MongoDB (`uk_food` database, `establishments` collection).
- Verified setup with PyMongo and PrettyPrint.

## Part 2: Database Updates
- Added new restaurant "Penang Flavours" in Greenwich.
- Removed establishments in Dover.
- Cleaned data by converting latitude/longitude and rating values to appropriate formats.

## Part 3: Exploratory Analysis
- Analyzed and answered key questions:
  1. Found establishments with hygiene score of 20.
  2. Retrieved establishments in London with RatingValue >= 4.
  3. Located the top 5 establishments near "Penang Flavours" with RatingValue of 5, sorted by hygiene score.
  4. Aggregated hygiene scores of 0 by Local Authority.
