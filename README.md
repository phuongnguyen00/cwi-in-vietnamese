# Complex Word Identification in Vietnamese 

Text Simplification has been an extensively researched problem in English, but has not been investigated in Vietnamese. We focus on the Vietnamese-specific Complex Word Identification task, the first step in the Lexical Simplification approach as defined by [Shardlow](https://aclanthology.org/P13-3015.pdf). Our experiments across three datasets constructed for other Natural Language Processing tasks in Vietnamese show that frequency is a strong signal in determining whether a word is complex, with a mean accuracy of of 86.87%. From the consistency across the datasets, we find that 10% of most frequent words in any corpus can be labelled as simple, and the rest as complex, although there may be more variability for smaller corpora.  

The three word lists used are Readability, Cluster and Classification, each of which contains simple words and complex words extracted from a corpus of the same name constructed for other Vietnamese NLP tasks. We also provide the features associated with each word in each word list: corpus-specific frequency, number of syllables, number of characters, and number of characters and diacritics.
