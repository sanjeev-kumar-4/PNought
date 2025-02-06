# PNought

Framework to enhance the decision making process for prioritization of feature development and enhancement.

#### Please access the presentation deck [here](https://docs.google.com/presentation/d/1PSlIuR3BfJ3gnY3hUGI--rgs5C7oOOc5DtT9vXSxfO0/edit#slide=id.g32d7154b98e_0_0)


### Methodology
- Pull data from multiple sources, both internal and external. These data consist of feature requests from active customers, customer feedback and product reviews from external sources like G2.
- Preprocess and standardize the data
- Cluster similar requests and feedbacks together into themes
- Create user stories within these themes and provide levers to rank these user stories
- Create a dashboard to visualize the results

### Tools and Technologies
- Notebook based preprocessing pipeline to preprocess the data
- GPT4o model from cloudverse
- BGE-M3 based text clustering
- Looker Studio for dashboard and visualization
