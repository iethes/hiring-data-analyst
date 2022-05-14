# Essay

This part is consisted of two essay questions for evaluating the creative and structural thinking of the candidate. Because there are no one true answer for this part, we highly encouraged the candidates to explain their thinking process and includes diagrams/illustration if needed. We also realized that not everyone is comfortable working with markdown file, so for this part feel free to create separate pdf files with the name `03_essay.pdf`

## Analysis of a Certain Shoes SME

Suppose you are a Data Analyst of Magpie that's working with a certain local Shoe Brands. The client is preparing themselves with the launch of a new product on several ecommerces in the coming month on the event of 07.07. To help this client you are expected to propose 2-3 possible analysis questions that may help our client. Give brief explanation of each analysis, what problem you'll target, any specific analysis you'll conduct, where would you get the data from, etc. (please limit your answer to around 500-700 words)

With the [following data](https://docs.google.com/spreadsheets/d/137ThHezo09Ykh-MIZt1hCL9Y52fLlAPUu-O37D6IOok/edit?usp=sharing), pick one of your proposed analysis and evaluate the feasibility. If feasible explain how you'll tackle the analysis, if not what would you do to make it feasible in the future? (please limit your answer to around 300-400 words)

## Structuring Datamart (Additional Point)

One of the key features of modern data analytics is the removal of sporadic datasource in favor of one place to put all our data. Enter Enterprise Data Warehouse, a denormalized view of items information, that contains daily information of the products that we track. Currently we're tracking ten-thousands of products from certain categories for several clients. From which we processed it to deliver multiple metrics for each of our clients. 
> Case study: we're tracking the multiple `accessories` categories from multiple ecommerce. And from those data we'll analyze the pricing and market share for each brand, and several ad-hoc analysis to our clients (all of which are monthly aggregate).
As a Data Analyst you'll work tightly with our team of Data Engineer, and in order to work efficiently you're given the freedom to request how the Data Engineer design the flow of data. 

Please describe your opinion about below points:
1. When is centralized datawarehouse still makes sense to be used, and when should we start creating datamart for each of our client. 
2. In this case, propose how you want the data to flow from the datasources (ecommerces) to intermediate tables, up until the data marts needed for analysis delivery.

Feel free to add additional assumptions to constraint your answer (please limit your answer to around 500-700 words)
