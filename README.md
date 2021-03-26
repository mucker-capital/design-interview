# Design Interview

You are the team lead at Neo Stocks Bots, a SaaS company that is building a platform that allows users to run their own algorithmic trading bots. 

You are in the design and architecture phase of this project and need to answer a set of critical questions that will ultimately decide how robust and scalable the platform is. 

Your team has decided to build the platform utilizing Alpaca's ticker data and trading APIs. Your users will only need to provide their Alpaca API key to get started. 

You have access to a prototypical trading algorithm known as the scalping strategy, which will serve as your foundation for this design exercise. 

#### Data

1. What kind of database would you use and why? e.g., RDBMS, doc store, columnar
1. What key database tables would you create and what are their relationships with each other, if any? 
1. What are the rough orders of magnitude for each dimension of your data in question? 

#### Architecture

1. SOA or monolith or microservices? Why?
1. serverless or not? Why?
1. Identify the steps required to refactor the codebase to support multiple users.

#### Testing

1. How would you implement testing? 
1. What types of testing would be included? Why? 

### Coding

The company wants to provide its users with helpful market analytics data. Please implement the following:

Requirements: Python, S&P 500 data

Identify the best and worst performing weeks within the last 12 months of the S&P 500 index where best and worst performing weeks is defined as the largest % gain or loss between a particular week's first day (Monday) and last day (Friday). The results should be in the form of the weeks identified by the Monday, eg. Week of August 10th, 2020.

Example Output:

```
Best Week: Week of August 10th, 2020 / +12%
Worst Week: Week of August 3rd, 2020 / -23%
```
