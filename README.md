# Book Recommendation Engine on Goodreads Data


## Aim
Given a set of books and ratings, develop a recommendation engine based on collaborative filtering.

## About the Data
The datasets were obtained from https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home which were scraped from public user shelves of goodreads.com by UCSD. Due to large size of the datasets, they are not uploaded here. Please download them from the given link. The datasets used are given below.

* goodreads_interactions.csv: contains user-book interactions
* goodreads_books.json.gz: contains complete book graph
* book_id_map.csv: contains the book IDs

## Code Notebook Descriptions

* search_recommend: Contains a search engine to identify the book IDs from book titles (could be partial). One can feed these IDs to the recommendation engine and get book recommendations based on other users with similar book interests.

* personalised_book_recommendation: Contains the recommendation engine that takes in my read-books data (containing book titles, my rating, etc.) and returns a set of recommended books for me using collaborative filtering.

## References
* Mengting Wan, Julian McAuley, "Item Recommendation on Monotonic Behavior Chains", in RecSys'18.
* Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "Fine-Grained Spoiler Detection from Large-Scale Review Corpora", in ACL'19.