# Telus Business Case - Contract Risk Scoring Model

Objective:

Looking at the textual contents and clauses of our contract with TELUS suppliers / vendors, we would like to identify risk in each contract and label each contract based on their risk level. Perhaps, this is an unsupervised algorithm and needs clustering model.

Background

The digital revolution in the world has created a vast ocean of data. This is available in all formats where data can be nicely structured into tables as well as unstructured found in text files, PDF files etc. There is a trove of information hidden in unstructured data that an organization can benefit from.

Here at TELUS we are looking to benefit from all the data that is contained in contracts. In particular, we are looking to extract the items below to help up assess and quantify risks for each contract :

1) Service Level Agreements (SLA): SLA is an agreement between two parties in a contract that specifies details of service subject of the contract. For example, customer based SLA is an agreement with one customer, covering all the services used by this customer. Let’s consider the relationship between you and your telecom operator. You use the voice services, SMS services, data services, and several other services of the telecom operator. For all these services, you have only one contract between you and the telecom operator. Similarly, if the IT service provider provides several services for the business and the customers, and if all the service levels are documented in one service level agreement for the provided services, it will be a customer based SLA).

We are interested to identify which contracts among thousands of contract at TELUS have SLA clause. We not only would like you to determine if a contract has SLA, but also extract the SLA terms and details.

2) Warranty: Does the contract contain any warranty clauses and if so extract it.

3) Signing Bonus: We want you to determine if there was any bonus offered to TELUS by signing the contract with the Vendor. Also, extract those text related to signing bonus. For instance, vendor X may offer $100,000 marketing fund once TELUS signs the contract as a bonus.

4) No Charge add-ons: Similar to signing bonus, there are some add-ons at no charge if TELUS sign up for the core services offered by vendor.

5) Marketing Development Funds: Market development funds or MDF are used in an indirect sales channel where funds are made available by a manufacturer or brand to help affiliates, channel partners, resellers, VARs, or distributors to sell its products and create local awareness about the national brand. Co-op Funds is a synonym for Market Development Funds.

6) Committed Funds: Value of the funds TELUS has committed to pay regardless how much service TELUS consumes.

7) Committed volume: Such as number of hours or quantity of goods that TELUS has agreed to consume.

8) Currency (USD or CAD): Some contracts can be in USD or CAD so we want to know the impact of currency fluctuations.

9) Contract Category: What is the category in which contract fall in. For instance, IT, fleet, field services, consulting, cleaning.

For each items you are tracking, we need to know what is your confidence score. For example, if you extract SLA, then how confident (90% or 80%) are you that there is an SLA in the contract. Same goes for all other items.

Scope:

These data points you are helping to extract from TELUS contracts are crucial for the success of our future steps when building machine learning solutions that can predict risk of each of our contract. These outcomes will be provided to TELUS executive leadership for better decision making.
