
First run the create index program:
python createIndex_tfidf.py stopWords.dat testCollection.dat testIndex.dat titleIndex.dat

Then run the query index program:
python queryIndex_tfidf.py stopWords.dat testIndex.dat titleIndex.dat

stopwords.dat is the stopwords file
testCollection.dat is the collection file
testIndex.dat is the main inverted index
titleIndex.dat is the title index
