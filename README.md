# Challenge 12 - NoSQL

This challenge demonstrates the usage of the NoSQL database MongoDB through Python with the pymongo package.

## Part 1

In the [notebook for part 1](NoSQL_setup.ipynb), I import the [establishments.json](Resources/establishments.json) file into MongoDB. I then add a single entry to the database ("Penang Flavours"), delete all "LocalAuthorityName" = "Dover" documents, and update the types for the field "latitude", "longitude" and "RatingValue" to appropriate numeric types or `null`.

## Part 2

In the [notebook for part 2](NoSQL_analysis.ipynb), I preformed some exploratory analysis by answering four questions.

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0?