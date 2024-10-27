# 10 - Distributed data modeling

## Description
In this chapter, we will examine data modeling within a modular, decentralized architecture centered on data products. We’ll start by clarifying what a data model entails and why intentionality in modeling is crucial. Then, we’ll explore various physical modeling techniques, assessing their strengths and how they fit into a distributed landscape. Finally, we’ll discuss conceptual data modeling, emphasizing its role in crafting high-level abstractions that guide the design and evolution of data products in a cohesive ecosystem 

## Chapter Headings  
* **Introducing data modeling**
  * What is a data model? 
  * Implicit and explicit models 
  * Data modeling process 
  * Data model representations 
  * Operational and analytical data modeling methodologies 
* **Distributed physical modeling**
  * Dimensional modeling 
  * Centralized dimensional modeling 
  * Distributed dimensional modeling 
  * Data vault modeling
  * Unified star schema modeling 
  * Managing the physical model lifecycle 
* **Distributed conceptual modeling**
  * Ubiquitous language 
  * From string to things 
  * Managing the conceptual model lifecycle 


## Skills learned
* **SKILL 1**: Understand the main phases of the data modeling process (alignment, refinement, and design) and their key deliverables (conceptual model, logical model, and physical model) 
* **SKILL 2**: Understand the main techniques of physical data modeling (dimensional modeling, data vault, unified star schema) and the ability to choose which one to use depending on the case. 
* **SKILL 3**: Understand the main techniques of conceptual data modeling (vocabularies, ontologies, etc.) and the ability to choose which one to use depending on the case. 

## Image list
* [Figure 10.1 - Data modeling process and deliverables](./images/chapter-10-Fig-1-Data-modeling-process.png)
* [Figure 10.2 - Sales star schema](./images/chapter-10-Fig-2-Star-schema.png)
* [Figure 10.3 - Kimball Data Warehouse Architecture](./images/chapter-10-Page-3-Kimball.png)
* [Figure 10.4 - Inmon Data Warehouse Architecture](./images/chapter-10-Fig-4-Inmon.png)
* [Figure 10.5 - Distributed dimensional modeling](./images/chapter-10-Fig-5-Distributed-dimensional-modeling.png)
* [Figure 10.6 - Data vault model](./images/chapter-10-Fig-6-Data-Vault-model.png)
* [Figure 10.7 - Data Vault Architecture](./images/chapter-10-Fig-7-Data-architecture.png)
* [Figure 10.8 - Distributed Data Vault modeling](./images/chapter-10-Fig-8-Distributed-data-vault.png)
* [Figure 10.9 - Sales and shipments facts](./images/chapter-10-Fig-09-Sales-shipments.png)
* [Figure 10.10 - Fan trap](./images/chapter-10-Fig-10-Fan-trap.png)
* [Figure 10.11 - Chasm trap](./images/chapter-10-Fig-11-Chasm-trap.png)
* [Figure 10.12 - Puppini Bridge](./images/chapter-10-Fig-12-Puppini-bridge.png)
* [Figure 10.13 - Distributed modeling architecture](./images/chapter-10-Fig-13-Target-model.png)
* [Figure 10.14 - Conceptual model types](./images/chapter-10-Fig-14-Conceptual-model-types.png)
* [Figure 10.15 - Ontology](./images/chapter-10-Fig-15-Ontology.png)


## Further reading 
For more information on the topics covered in this chapter, please see the following resources: 

* [My Definition of Data Modeling (for today)](https://joereis.substack.com/p/my-definition-of-data-modeling-for ) - J. Reis (2024) 
* [The Align, Refine and Design Approach to Data Modeling](https://www.youtube.com/watch?v=-5uZlyAn3Vk ) – S. Hoberman 
* [The Data Dichotomy: Rethinking the Way We Treat Data and Services](https://www.confluent.io/blog/data-dichotomy-rethinking-the-way-we-treat-data-and-services/) – B. Stopford (2016) 
* [Data on the Outside vs. Data on the Inside](https://queue.acm.org/detail.cfm?id=3415014 ) – P. Helland (2020) 
* [The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling](https://a.co/d/dOnBzxJ ) - R. Kimball, M. Ross (2013)  
* [Building the Data Warehouse](https://a.co/d/efuuDO6) - W. H. Inmon (2005)   
* [Building a Scalable Data Warehouse with Data Vault 2.0](https://a.co/d/cNURox4) - D. Linstedt, M. Olschimke (2015)   
* [The Unified Star Schema: An Agile and Resilient Approach to Data Warehouse and Analytics Design](https://a.co/d/eZAbGyY) – B. Inmon, F. Puppini (2020) 
* [Semantic Modeling for Data: Avoiding Pitfalls and Breaking Dilemmas](https://a.co/d/8WQDBJa) - P. Alexopoulos (2020)  
* [RDF 1.1 Concepts and Abstract Syntax](https://www.w3.org/TR/rdf11-concepts/)
* [RDF 1.2 Turtle](https://www.w3.org/TR/rdf12-turtle/)
