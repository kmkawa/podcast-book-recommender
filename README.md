# Podcast & Book Recommender using BERT Embeddings

After just finishing a fabulous book recommended by a friend, typing into Google to find the next great read, hitting return, and the same Goodreads article about the same top ten books of the last year is the only thing that pops up. Or an article about how everyone needs to read the classics. Book recommendations often come from the same websites hyping each other up and supplying the same books based on ratings alone. The experience is the same with finding new podcasts, too. Spotify’s once human-recommended songs and podcasts have been replaced by AI, only focused on numbers. So we wanted to solve this AI-generated problem using AI ourselves. But instead of focusing on ratings by critics or a popularity contest, we are using similarity and distance to recommend books and podcasts based on the content of the books and the wishes of a reader or listener. 

How did we achieve this? First, we collected a library of books and podcasts and got their descriptions and additional metadata. Then, we turned the descriptions into embeddings—high dimensional vectors which capture meaning—using the BERT encoder. Next, we chose a similarity algorithm, hooked up additional parameters, and got the most similar podcasts or books to the user input. And finally, output a recommendation! The sections below go into more detail about the steps outlined above, so read on to understand and even get your own recommendations!


## Links to more info & data
Link to blog: https://docs.google.com/document/d/12CeQjQEv9j8VV-0CZWLNpv-PrQDg0xgwxMYmERtg8bs/edit?tab=t.keh16tmv01ed

Link to podcast data: https://drive.google.com/file/d/10T5dTDKJfcMiIdPsgT4ySr73LKRn0RLj/view?usp=sharing

Link to book data: https://drive.google.com/file/d/1zDpeQRq4UMKoM83f958mxIK4hxdYodgH/view?usp=sharing
