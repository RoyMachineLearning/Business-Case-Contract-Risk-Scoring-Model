# Telus Business Case - Contract Risk Scoring Model

Objective:

Looking at the textual contents and clauses of our SOW (Statement of Work) with TELUS suppliers/vendors, we would like to identify risk in each SOW and label each SOW based on their risk level. Perhaps, this is an unsupervised algorithm and needs clustering model.

Background

The digital revolution in the world has created a vast ocean of data. This is available in all formats where data can be nicely structured into tables as well as unstructured found in text files, PDF files etc. There is a trove of information hidden in unstructured data that an organization can benefit from.

Here at TELUS we are looking to benefit from all the data that is contained in SOW. In particular, we are looking to extract the items below to help up assess and quantify risks for each SOW :

1) Work Description: What work is agreed to be done in each of the SOWs? 

2) ETA or delivery date: What is the expected completion or delivery date?

3) Headcount & rates: Number of resources allocated to the project and at what rate per resource?

4) Nature of resources: What are the tangible and intangible resources agreed to be provided (human resources, hardware, application, hours of development, building ETL, digging hole)?

5) Location of work: The place the work is agreed to be performed; often TELUS office or a physical location defined by TELUS. It also can be at vendor location. Some SOWs do not have location as there is no locality concerned.

6) Committed Funds: Value of the funds TELUS has committed to pay regardless how much service TELUS consumes.

7) Committed volume: Such as number of hours or quantity of goods that TELUS has agreed to consume.

8) Currency (USD or CAD): Some SOWs can be in USD or CAD so we want to know the impact of currency fluctuations.

9) SOW Category: What is the category in which SOWs fall in. For instance, IT, fleet, field services, consulting, cleaning.

For each items you are tracking, we need to know what is your confidence score. For example, if you extract SLA, then how confident (90% or 80%) are you that there is an SLA in the SOW. Same goes for all other items.

Scope:

These data points you are helping to extract from TELUS SOW are crucial for the success of our future steps when building machine learning solutions that can predict risk of each of our SOW. These outcomes will be provided to TELUS executive leadership for better decision making.  While for class grade point of view, I can evaluate your grade based on the way you identify above risk element and extract them, but I would encourage you to take it to the next step to make it a full NLP project by thinking of building a clustering algorithm that based on your data points, creates three clusters for the SOW;

- low risk
- medium risk
- high risk

The benefit of building cluster of SOW, you are able to see for yourself how your feature engineering on text results in a true AI/ML project. Perhaps should you decide to build the clustering model, you need to collect more SOWs to create a sizeable dataset for training.

We understand some of the above metrics may be challenging to understand and distinguish and hence will provide on-request meetings with our team members to help you succeed in what you are doing.
