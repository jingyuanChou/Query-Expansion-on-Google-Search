# Query-Expansion-on-Google-Search


1. This project is aimed to expand query request when people type words to search on Google, for example, type "I LOVE" on the browser, there will be "You" follows, or something matches the most frequent sentences.
2. This project involves Java, Hadoop, Map/reduce, docker, Linux. 
3. there are three steps for this project:
    (1). Built an N-Gram Library based on the text corpus using Map/Reduce.
    (2). Constructed Language Model according to the N-Gram Library and Statistic probability.
    (3). Injected the data Language Model generated into database by reducer.
    (4). Implemented real-time auto-completion system with the constructed database and run on webpages built by Ajax, jQuery, PHP.
