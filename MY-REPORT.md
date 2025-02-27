![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# AI Travel Time Bot

This project will descibe how to implement a bot that is capable of advising of the best way of travel to get to your destination. 

* Authors: Alexander Williams
* Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

  
# Research Question 

How can we create a bot that is capable of creating product requirements for an accurate travel times for specific modes of transport, as well as simplifying it into an easily digestible blurb of text.

## Arguments

#### What is already known about this topic

* You can use any number of map applications to get the best route according to a platform.
* Different apps have different info sources, as well as different interfaces that makes comparing data hard.
* Could we combine different map time data into a model to give an answer most likely to be agreed upon by multiple applications?
* Can AI create the requirements for such an application?

#### What this research is exploring

<!-- Free-format; use the topics that are applicable to your exploration  -->

* We employ Prompt Template Prompting, Chain of Thought Prompting, and Self Ask to steer the AI in the right direction. 
* We are building an AI bot that can create product requirements and analysis for a travel time application.
* We are exploring AI's ability to create requirements based on place, and programming language.

#### Implications for practice

<!-- Free-format; use the topics that are applicable to your exploration  -->

* It will be easier to ask an AI how to create an application for a specific area.
* It will optimize how long it  takes to build, as well as be much more accurate than an international offering. 
* We will better understand the work involved

# Research Method

To compare these techniques efficacy, I compared it against a one-shot system leveraging only prior trained information.

<!-- WHEN APPLICABLE AND AVAILABLE -->

# Results

I was able to get much more strucutred data from the specialized prompting techniques in comparision to a baseline raw query. This shows that is already easier to use this workflow when starting from scratch. Using the Self-Ask technique allowed to specify details about the requirements to further narrow down the future implementation. This was very helpful. 

# Further research

For further research I would want to feed the model historical data from various map/travel sources to help compose this. In addition this will help with things like additional training to progressively improve things like suggested weighting between each source when creating the app.