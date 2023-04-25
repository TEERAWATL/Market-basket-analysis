# Market-basket-analysis

This program demonstrates a simple example of Market Basket Analysis using the Apriori algorithm in Python. Market Basket Analysis is a technique used to identify associations and relationships between different items in a dataset, such as items purchased together in a store.

## Dependencies
To run this program, you'll need the following Python libraries:

pandas: A library for data manipulation and analysis.
apyori: A library that provides a simple implementation of the Apriori algorithm for association rule mining.

## Output Description
The output DataFrame contains the following columns:

items_base: The antecedent, or the item(s) on the left-hand side of the association rule.

items_add: The consequent, or the item(s) on the right-hand side of the association rule.

support: The proportion of transactions that contain both the antecedent and the consequent items.

confidence: The probability of finding the consequent in a transaction, given that the antecedent is present.

lift: The ratio of observed support to expected support if the antecedent and consequent items were independent. A lift greater than 1 indicates that the antecedent and consequent items are more likely to be purchased together than individually.
