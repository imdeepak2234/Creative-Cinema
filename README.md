# Creative-Cinema
Creative Cinema is a content based recommender system recommends movies similar to the content of a given movie.
The details of the movies(title, genre, overview, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the TMDB id of the movie in the API.
# How to get the API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. You will see the API key in your API sidebar once your request is approved.
# How to run the project?
1. Install all the libraries mentioned in the requirements.txt file.
2. Clone this repository in your local system.
3. Replace YOUR_API_KEY in the app.py file.
4. Open the command prompt from your project directory and run the command python app.py.
5. Follow the instructions shows on cmd to run the webpage in browser.
6. Hurray! That's it.
# Similarity Score :
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
# How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png
