MOVIEDEX

Create a project called moviedex-api and initialize it as an Express app to meet the following requirements:

1. Users can search for Movies by genre, country or avg_vote
2. The endpoint is GET /movie
3. The search options for genre, country, and/or average vote are provided in query string parameters.
4. When searching by genre, users are searching for whether the Movie's genre includes a specified string. The search should be case insensitive.
5. When searching by country, users are searching for whether the Movie's country includes a specified string. The search should be case insensitive.
6. When searching by average vote, users are searching for Movies with an avg_vote that is greater than or equal to the supplied number.
7. The API responds with an array of full movie entries for the search results.
8. The endpoint only responds when given a valid Authorization header with a Bearer API token value.
9. The endpoint should have general security in place such as best practice headers and support for CORS.
