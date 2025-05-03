https://docs.confluent.io/cloud/current/_glossary.html

* TODO:

# Stream Catalog

* 👀== inventory of your organization’s data assets 👀
* supports
  * data governance
  * data discovery 
* | Confluent Cloud Console's Data Portal,
  * enables you to,
    * find event streams ACROSS systems,
    * search topics -- by -- name or tags
    * enrich event data
      * Reason: 🧠 increase value & usefulness🧠 
* uses -- through -- REST & GraphQL APIs, 
  * search schemas,
  * apply tags | records or fields,
  * manage business metadata,
  * discover relationships ACROSS data assets

# Stream Designer
* TODO:

# Stream Governance

* := 👀collection of tools + features /
  * -- provide -- 
    * | data in motion, data governance 👀
      * == manage
        * availability, 
        * integrity,
        * security of data -- used ACROSS -- organizations,
      * -> help -- with --
        * standardization,
        * monitoring,
        * collaboration,
        * reporting, 
  * == 
    * data quality tools
      * Schema Registry, schema ID validation, and schema linking
    * built-in data catalog capabilities -- to -- ACROSS systems,
      * classify,
      * organize,
      * find event streams 
    * [stream lineage](#stream-lineage)

# Stream lineage

* := data's life cycle or history
  * == 's origins + transformations + consumption
    * == from source -- to -- it's destination
  * Reason: 🧠data -- moves through -- various stages | data pipelines, applications, and systems🧠
* allows
  * visualize complex data relationships
  * uncover insights -- via -- maps of event streams
    * interactive,
    * E2E
* uses
  * track
    * data quality,
    * data governance,
    * data security

