# Intro

You are asked to build a very simple data viz application.

The metric observed is the monthly volume of searches in Google for a given list of keywords, structured in a category tree. It shows how often terms or phrases related to a category are searched for in Google each month.

# Level 1 - Fetch and display data

We want to display in a nice graph the evolution of the monthly search volume for the top-level category. We would like to display the last 24 months by default and we would be able to change the selected period to navigate into the data.

The `GET /api/volumes/250162.json` endpoint returns the total monthly search volume, for each month, over the 48 months prior to July 2022, and for all monitored keywords.

Then go to [next level](../level2)
