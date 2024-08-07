# 05 - Designing and implementing data products

## Description
In this chapter, we will explore the process of designing a data product based on the requirements identified during
the analysis phase. Our journey will begin by delving into advanced techniques for defining scope,
interfaces, and the relationships with the external ecosystem. We'll then dissect the core
components of a data product, outlining their development process and showing how to describe
them through machine-readable descriptor document. Lastly, we'll embark on a journey through
the data flow within a data product, examining components responsible for sourcing, processing,
and serving data.

## Chapter Headings  
* **Designing data products and their interactions**
  * Understanding data product local environment
  * Understanding data product global ecosystem
  * Understanding data product internals 
* **Managing data product metadata**
  * Describing data products 
  * Introducing the Data Product Descriptor Specification (DPDS) 
  * Describing interface components in DPDS
  * Describing internal components in DPDS 
* **Managing data product data**
  * Sourcing data 
  * Processing data
  * Serving data 
 
## Skills learned
* **SKILL 1**: Ability to accurately define the scope of a data product and accordingly design the
relationship with the external ecosystem through context mapping
* **SKILL 2**: Ability to manage the discovery, interpretation, and acquisition of data used by the
data product, sourced from both other data products and external application systems.
* **SKILL 3**: Skill in crafting internal data transformations while striking the optimal balance
between development autonomy and streamlining the technological stack.
* **SKILL 4**: Expertise in determining the optimal data serving methods for generated data to
enhance its accessibility and reuse across various use cases.
* **SKILL 5**: Understanding how to formally describe the designed data product to ease its
utilization by potential consumers and to facilitate the automation of its life cycle.

## Image list
* [Figure 5.1 - Data product local context](./images/chapter-05-Fig-01-Data-product-local-context.png)
* [Figure 5.2 - Digital Sales Data Product’s local environment](./images/chapter-05-Fig-02-Digital-sales-product-local-environment.png)
* [Figure 5.3 - Data exchange modalities](./images/chapter-05-Fig-03-Data-exchange-modalities.png)
* [Figure 5.4 - External Systems](./images/chapter-05-Fig-04-External-systems.png)
* [Figure 5.5 - Data product map](./images/chapter-05-Fig-05-Data-product-map.png)
* [Figure 5.6 - Context map](./images/chapter-05-Fig-06-Context-map.png)
* [Figure 5.7 - Data product internal components ](./images/chapter-05-Fig-07-Data-product-internals.png)
* [Figure 5.8 - Data product descriptor structure](./images/chapter-05-Fig-08-DPDS-structure.png)
* [Figure 5.9 - Promises Object Structure](./images/chapter-05-Fig-09-Promises-object.png)
* [Figure 5.10 - Standard Definition Object Structure](./images/chapter-05-Fig-10-Standard-definition-object.png)
* [Figure 5.11 - Expectations Object Structure ](./images/chapter-05-Fig-11-Expectations-object.png)
* [Figure 5.12 - Obligations Object Structure ](./images/chapter-05-Fig-12-Obligations-object.png)


## Further reading 
For more information on the topics covered in this chapter, please see the following resources: 

* [Context Mapping](https://github.com/ddd-crew/context-mapping ) – DDD-Crew 
* [Building an Event-Driven Data Mesh](https://www.amazon.com/Building-Event-Driven-Data-Mesh-Architectures/dp/1098127609) – Adam Bellemare (2023)  
* [What is Composable Business Application?](https://www.youtube.com/watch?v=_oHqiDWTrAQ&t=1333s ) – Massimo Pezzini (2023) 
* [Data Product Descriptor Specification](https://dpds.opendatamesh.org/) – Open Data Mesh Initiative  
* [Data Product Specification](https://github.com/agile-lab-dev/Data-Product-Specification) - AgileLab   
* [Open Data Contract Standard](https://github.com/bitol-io/open-data-contract-standard) - BITOL  
* [Functional Data Engineering :a modern paradigm for batch data processing](https://maximebeauchemin.medium.com/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a) - Maxime Beauchemin (2018)   
* [Thinking in Promises: Designing Systems for Cooperation](https://www.amazon.com/Thinking-Promises-Designing-Systems-Cooperation/dp/1491917873) - M. Burgess (2015) 
