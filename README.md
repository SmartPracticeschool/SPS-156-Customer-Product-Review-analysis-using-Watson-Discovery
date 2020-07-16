# SPS-156-Customer-Product-Review-analysis-using-Watson-Discovery
## Customer Product Review analysis using Watson Discovery

Let’s imagine, you have a ton of documents (JSON, HTML, PDF, Word, and so on) and your task is  to find the insights that are hiding in those documents. What are you going to do in this situation? You’re going to read and analyze each of the documents, but it is a time consuming process

Fortunately, IBM Watson Discovery was created to help us go through situations like this. IBM Watson Discovery is a cognitive search and content analytics engine that you can use to identify patterns, trends and actionable insights from structured and unstructured data (JSON, HTML, PDF, Word, and more) with speed and accuracy to drive better decision-making.

I can say that Discovery can handle every hardest thing for you. You just create an instance of Discovery, inject and persist data into collections (collection as a box where you store data in Discovery). Discovery will automatically ingest (convert, enrich, clean, and normalize), store, and query data to extract actionable insights. After that, you can easily search and query what you want from the original data.

### Introduction

IBM Watson Discovery Service helps developers quickly create cognitive applications that extract values from large amounts of structured and unstructured data you can perform following tasks using Watson Discovery  service

* Explore and discover insightful information present in the data
* You can leverage Watson Discovery   SDKs, web based pooling and WDS API to bring cognitive insights to your custom applications 
* Can be used to address many different use cases from customer insights to question and answer scenarios.

![Image](C:\Users\hashim irfan\Desktop\Sites\SPS-156-Customer-Product-Review-analysis-using-Watson-Discovery\Image\download (3).png)

### Workflow

1. firstly, you upload all documents in the database to Watson Discovery Service by Upload function.
2. Watson discovery Service gets the documents and starts ingesting (convert, enrich, clean, and normalize),
3. store, and query data to extract actionable insights.
4. At this time, you'll use the Search function to get the results from Watson discovery, and rates each of the results,
5. mark the results as relevant or irrelevant (In this step, training data will be created).
6. When you're finished rating the documents, you'll use Study function to upload all training data to Watson discovery to train.
7. Watson discovery will spend 30 minutes for training. when the training process finished, use the Search function
8. and you'll see more suitable results