https://docs.confluent.io/cloud/current/connectors/index.html

* Apache Kafka® Connectors
  * types
    * pre-built,
    * [custom connectors](connectors.bring-your-connector.overview.md)
  * fully-managed,
  * make it easy to
    * 👀INSTANTLY connect -- to -- popular 
      * data sources == source connector 👀
        * entire databases and streams table updates -- are ingested to -- Kafka topics
        * FROM ALL your application servers,
          * collect metrics
          * store these metrics | Kafka topics
          * making the data available / stream processing -- with -- LOW latency
        * _Example:_ Microsoft SQL Server Source connector
      * sinks == sink connector 👀
        * from Kafka topics, data -- is delivered into -- secondary indexes (_Example:_ Google BigQuery, Amazon S3)
  * [limitations](connectors.limits.md)
  * [CwC program](client-apps.connect-w-confluent.md)

* TODO: