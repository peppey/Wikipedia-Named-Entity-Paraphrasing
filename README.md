# Wikipedia Paraphrase Scraping

This is mainly for finding paraphrases for terms. Synonyms can be found more easily.

For many tasks we need paraphrases or synonyms of a term. 
When we want to use the word "Myanmar", it might be useful to use "Burma", as well. 

Synonyms like this can be found in Wiktionary or WordNet. However, we sometimes also need paraphrases.
When using "Elizabeth II" for a task, it might be us will be helpful to include "The Queen" or "Her Majesty", as well.

While synonyms of places like Myanmar can be found on WordNet, paraphrases for persons cannot be found there. 

This approach uses all the link captions that Wikipedia uses for links that lead to an article like "Elizabeth II". For
example, if a Wikipedia article about Great Britain mentions the word "The Queen", which is linked to the article "Elizabeth II", 
then the paraphrase "The Queen" will be included in the list of paraphrases for "Elizabeth II".

The approach is too slow for finding paraphrases e.g. in a real-time search, but can be run through a list of named entities. 
The paraphrases can then be saved for later.
