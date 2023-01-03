# Principles of System Design

*Rule #1:* When working with a *read-heavy system*, it's a good idea to consider a *caching* mechanism.

*Rule #2:* When working with a *write-heavy system*, it's a good idea to consider using a *Message Queue* for Async Processing.

*Rule #3:* When working with a *low latency system*, it's a good idea to consider using *Cache & CDN (Content Delivery Network)*.

*Rule #4:* If we require an *ACID-compliant system*, we should use *RDBMS or SQL Database*. 

*Rule #5:* If the data is unstructured and *does not require ACID qualities*, we should use a *No-Sql database*.

*Rule #6:* If the system requires *complicated pre-computation*, such as a news feed, we should use a *Message Queue and CDN*.

*Rule #7:* If the system contains *complex data like as movies, photos, files*, and so on, we should use *BLOB/Object Storage*.

*Rule #8:* If the system involves searching large amounts of data, we should consider employing a *search index, attempts, or search engine such as ElasticSearch/OpenSearch*.

*Rule #9:* If the system demands SQL Database Scaling, we should investigate *Database Sharding*.

*Rule #10:* If the system demands *High Availability(HA), Performance, Throughput*, we should consider using a *Load Balancer*.
