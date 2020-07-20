# Album-Review-Ratings
Build a model to take as input an album review and predict the rating out of 10 points
The model focuses solely on reviews taken from Pitchfork.com. Since my favorite genre of music is rap/hip-hop, I've focused on analyzing those albums only

In the file the file AlbumReviewData contains a CSV file of the 120 most recent album reviews in rap/hip-hop. It is organized into two columns "Review" and "Score". The former is a raw string of the review, the former the score (out of 10). Each row is indexed by the album title

The notebook AlbumRate contains both the webscraping, and as of now, a quick analysis using vectorization of the text input. This will be drastically improved upon in future versions.

Part of the issue with this analysis, is that even an expert human reader might have a difficult time discerning the score; much like two students submitting identical papers to a teacher, then receiving two different scores
