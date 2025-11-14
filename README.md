A Python-based movie recommendation system that suggests similar movies based on their content.

Method: Content-Based Filtering

Dataset: TMDB 5000 Movies & Credits

Core Logic:

Combines text features (genres, keywords, cast, director, overview) into a single corpus.

Uses CountVectorizer to create a Bag-of-Words model.

Calculates cosine_similarity between all movie vectors to find and return the top 5 most similar movies.

Libraries: Pandas, NLTK, Scikit-learn
