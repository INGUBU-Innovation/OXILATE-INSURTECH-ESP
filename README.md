# OXILATE: A COLLECTIVE INTELLIGENCE FRAMEWORK WITH GPT-BASED ASSISTANT


# The motivation

TyP and SII CONCATEL have focused on the use case: "Improved services and tools that support the Smart Insurtech lifecycle".  Insuretech, is created after joining the words: insurance and technology. Insurtech or Insuretech, are the associated words to refer to this term, although Insuretech is used much less frequently.

Insurtech, in a very summarized form [1] is a term that refers to the concept or the ability to apply the potential of all the new technologies to the insurance sector.

These digital technologies make it possible to bring greater quality and efficiency to the insurance industry. They enable greater traceability, scalability, data quality and security, which is essential for the industry.

The use case that TyP and SII CONCATEL have worked on, called "Service enhancements and tools that support the Smart Insurtech lifecycle", aims to provide insurance companies with new methods and services to a market characterized by constantly changing consumer patterns.

The Insuretech context, like the other industries targeted by the project, faces the challenges outlined in OXILATE:

- Increased complexity due to dynamic business models.

- Need to evolve. 

- Impact of globalization and new scenario associated with new data access technologies.

As reflected in the "Cognizant Perspectives" [2] series of articles, the insurance industry faces an added challenge: a large part of its workforce will retire in the coming years.

In addition, a recent study by Oxford Economics [3], established that more than 83% of insurance executives rely on consultants and temporary workers to respond to market demand. TYP, through the generation of expert knowledge from the entire life cycle of products and services and the provision of improved tools to professionals in its different business units, seeks to facilitate:

- Respond to the needs of including inexperienced workforce.

- Development of new products and services.

- Solve complex challenges at a lower cost.

- Create a better value proposition.

One way to meet this challenge is through techniques that enable "Collective Intelligence" techniques. This is where OXILATE, and the research and development activities provided by TYP and SII CONCATEL  in the domains of Knowledge Graphs combined with Machine Learning techniques will make the difference.

By enabling CI techniques based on ML techniques, allowing the inclusion of expert knowledge, companies in the insurance sector will be able to enable a larger number of workers to execute specialized functions in less time and create predictive models applicable to different aspects and/or business units (risks, new products, cancellation rates...).

OXILATE will be a meeting point for customers and industry professionals, and will connect companies to new technologies, providing professionals with intelligent tools that support them throughout the product lifecycle.

For the definition of the use case, during this first milestone, different meetings have been held with key entities of the sector, to first understand -and then generalize- the context of the sector. In order to speed up and dynamize the meetings with users and interested entities, a presentation has been generated, which has facilitated the involvement of different users in the definition of requirements.

![imagen-OXILATE-ESP-1](https://user-images.githubusercontent.com/73121692/214376210-9d698bdf-ae7c-4701-bb83-3125bf15ce4d.png)
  
  
![imagen-OXILATE-ESP-2](https://user-images.githubusercontent.com/73121692/214376786-bbbe0b02-ca0e-44c7-87c0-f7ba360c53df.png)



Illustration 1-2 Use Case Presentation - Insurtech Digital Assistant

After defining the use case, it was decided to define OXILATE as the CHATGPT FOR COMPANIES (formerly ALEXA for companies), in order to facilitate the assimilation of the concept by those initial target companies in the insurance sector immersed in the initial stages of digital transformation, which understand that they must evolve, but have not assimilated the benefits of new technologies and concepts. An assistant to help these companies leverage their knowledge and meet talent gaps by reducing overhead, bolstering performance and ensuring rapid adaptation to emerging market demands to shorten development lifecycles.




# System Diagram

The OXILATE-INSURTECH framework is composed of four main components. 

## Data acquistion module

![OXILATE-DATA-ACQUISITION-HL-DIAGRAMA](https://user-images.githubusercontent.com/73121692/215027894-1c99362c-dc16-4e5a-a467-1a96918e9406.png)

This module systematically collects the company's operational information. For this, we rely on different ETL components adapted to the solutions deployed at the customer. This information (raw text) is filtered and processed with different models. One model classifies the text, identifying whether it is information on sales, purchases, cancellations, registrations or modification processes. In addition, the sentiment of the text is recorded. All this information is recorded in the knowledge graph. One of the most innovative components is the one that allows, once the entities, topics and sentiment are identified, to register the information in the knowledge graph.


## Knowledge capturing and adaptation module

![OXILATE-HIGHLEVELDIAGRAM - OXILATE-KNOWLEDGE-CAPTURING](https://user-images.githubusercontent.com/73121692/215027947-b00946cb-1331-4496-819e-54e651300ec3.png)

This module records information on procedures and tutorials. It processes all existing information. This information is processed in different ways: on the one hand, it is summarized and on the other hand, it is classified: sales, purchases, cancellations, registrations... This information is recorded in the knowledge network. On the other hand, Machine Learning tools applied to knowlege graphs (link prediction, similarity, closeness...) continuously process the graph. This graph analysis process generates intents (insights, predictions...) that are sent to the AI-generated Knowledge Validator. The intents can also be generated by operational events: low, high, budget acceptance... These intents are validated by the expert. 

## AI-based Assistant module


![OXILATE-HIGHLEVELDIAGRAM - OXILATE-SMARTSERVICEAPI](https://user-images.githubusercontent.com/73121692/215027964-9cffeeae-b0c7-43f0-89d1-fcd65f01e0db.png)

This module is combining the power of Knowledge Graphs and GPT. Recently, this has been defined as  "Retrieval Augmented Generation"[4][5]. That is, we combine the power of a knowledge graph, relying on links and nodes that defined with natural language, and the power of GPT to, given pieces of text, combine all pieces and create a sound speech. Also, in the other direction, the GPT-based few-shot learning [6] allows to ease the ingestion of information in the graph. 


## User Interface: implementation for insurance brokers


![UI-Sample](https://user-images.githubusercontent.com/73121692/215028219-6901c840-3321-4ed3-a471-0f71bff049a2.png)


# References

[1] Insurtech - https://es.wikipedia.org/wiki/Insurtech

[2] https://www.cognizant.com/perspectives/overcoming-the-insurance-talent-gap-with-collective-intelligence-part1

[3] http://www.oxfordeconomics.com/publication/open/250945

[4] https://arxiv.org/abs/2005.11401

[5] https://ai.facebook.com/blog/retrieval-augmented-generation-streamlining-the-creation-of-intelligent-natural-language-processing-models/

[6] https://huggingface.co/blog/few-shot-learning-gpt-neo-and-inference-api

