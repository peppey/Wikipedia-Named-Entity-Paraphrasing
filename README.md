# Wikipedia Named Entity Paraphrasing

For including keywords in a text search, it is often helpful to include paraphrases or synonyms of the keyword, as well. 
When searching for "Myanmar", it will be helpful to include "Burma" in the search. When searching for "Elizabeth II", it
will be helpful to include "The Queen" in the search.

While synonyms of places like Myanmar can be found on WordNet, paraphrases for persons cannot be found there. 

This approach uses all the link captions that Wikipedia uses for links that lead to an article like "Elizabeth II". It is too slow for finding
the synonyms at the same time as searching (this should only take 1 or 2 seconds) but can be run through a list of named entities. The synonyms
can then be saved for later.
