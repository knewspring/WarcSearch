## WarcSearch

Information Retrieval HW 1

WarcSearch searches Web Archives (WARC) and based on a user's query retrieves results ranked by TFIDF.

#### Usage

	java -jar warcsearch.jar -a /path/to/archive.warc -q query

#### Thx to
1. [Apache Lucene](https://lucene.apache.org/core/4_7_0/index.html) - indexing and search
2. [Java Web Archive Toolkit](https://sbforge.org/display/JWAT/Documentation) - parsing WARC
3. [Apache Commons CLI](http://commons.apache.org/proper/commons-cli/) - parsing cli arguments
4. my mother