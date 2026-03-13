# Fabric Ontology

## Fabric Lakehouse
Fabric Lakehouse provides the governed data layer from which the Semantic Model is created, enabling Ontology IQ to understand business entities, metrics, and relationships for intelligent AI-driven analytics. If you dont have 
![](Image/LakehouseMain.png)

Below are asic objects considered for the Retail Ontology:
|Schema            |Table                  |Description                  |
|------------------|-----------------------|-----------------------------|
|Marketing            |Campaign                  |Campaign related data                  |
|Marketing            |Customer                  |Customer information                  |
|Sales            |offlinesales                  |Store sales details                  |
|Sales            |onlinesales                  |Online sales/ecommerce data                  |
|Operation            |Inventory                  |Product inventory details                  |
|Operation            |Sales                  |Sales operation details                  |
|Operation            |StoreInventory                  |Store level inventory                   |
|DigitalExperience            |clickstream                  |Customer visited information                  |
|DigitalExperience            |feedbacks                  |Customer feedback on sales                  |
|DigitalExperience            |webtraffic                  |Customer footprint on purchase                  |


## Creating Semantic Model using Lakehouse
*	Build a business-friendly semantic layer for retail analytics.
*	Creating domain and business specific calculated measures and KPIs
*	Establishing relationship among objects.
  ![](Image/SemanticModel.png)

### Creating RTI in Eventhouse
* Eventhouse:
** Retail_Eventhouse created to store streaming data coming from EventHub/Kafka
** Database created as default while creating eventhouse. 


