Dataset
-------

The [Book-Crossings dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) contains:

-   1.1 million book ratings (scale: 1-10)
-   270,000 unique books
-   90,000 users
-   Format: User-Item-Rating interactions

Challenge Requirements
----------------------

-   Implement a K-Nearest Neighbors recommendation algorithm
-   Process and handle the large-scale dataset efficiently
-   Create a function that takes a book title or user ID and returns personalized book recommendations

Technical Goals
---------------

-   Handle sparse rating matrices
-   Implement appropriate similarity metrics
-   Balance recommendation accuracy with computational efficiency
-   Provide justification for parameter choices (e.g., value of K, similarity metric)

Evaluation Metrics
------------------

Your solution will be evaluated on:

-   Recommendation relevance
-   Algorithm performance and scalability
-   Code quality and documentation
-   Handling of edge cases (new users, cold start)
