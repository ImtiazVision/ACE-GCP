### Cloud BigTable

Cloud Bigtable: is a wide-column NoSQL database similar to Cassandra or HBase. It requires a cluster of machines be created and cluster can be easily resized for scalability. Multiple clusters can be created and replicated. Each row in a Bigtable must have a unique key. Only index available is the key and very fast data retrieval as long as the key is searched. Bigtable is optimized for very fast data retrieval. Cloud Bigtable design idea is "simplify for speed". The Row key is the index and we get only one index. Bigtable scales UP well.
