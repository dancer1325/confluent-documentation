https://docs.confluent.io/cloud/current/sr/index.html

* Schema Registry 
  * == centralized repository / 
    * allows
      * | topic message data, 
        * manage schemas
        * validate schemas 
      * serializing and deserializing -- over the network -- the data  
  * uses
    * by producers & consumers, to ensure
      * data consistency
      * data compatibility
        * Reason: 🧠 schemas evolve🧠 
  * == data governance's key component
    * Reason: 🧠
      * ensure data quality,
      * adherence to standards,
      * visibility | data lineage,
      * audit capabilities,
      * collaboration ACROSS teams,
      * efficient application development protocols🧠

## Quick starts
* Schema Registry tutorials
  * goal
    * enable client applications -- to -- read & write Avro data
    * check schema version compatibility
    * use UIs -- to manage -- schemas
  * types
    * [Confluent Cloud Schema Registry Tutorial](sr.schema_registry_ccloud_tutorial.md)
    * [Confluent Platform Schema Registry Tutorial](platform.current.schema-registry.schema_registry_onprem_tutorial.md) 

* TODO:


# TODO: