# Association Rule Mining using Apriori and FP-Growth

## Project Overview

This project demonstrates the application of Association Rule Mining techniques on a real-world grocery transaction dataset. The objective is to discover frequent purchasing patterns, generate meaningful association rules, and compare the performance of Apriori and FP-Growth algorithms.

## Dataset

**Name:** Groceries Market Basket Dataset

The dataset contains transactional records of grocery purchases, where each transaction consists of the items purchased by a customer during a single shopping visit.

## Objectives

- Prepare transaction data for market basket analysis.
- Transform transactions into one-hot encoded format.
- Generate frequent itemsets using the Apriori algorithm.
- Generate association rules using support, confidence, and lift.
- Apply the FP-Growth algorithm and compare its results with Apriori.
- Compare the execution time of both algorithms.
- Analyze the effect of different support and confidence thresholds.
- Visualize the strongest association rules based on lift.

## Algorithms

- Apriori
- FP-Growth

## Results

- Successfully generated frequent itemsets from transaction data.
- Extracted association rules using support, confidence, and lift metrics.
- Compared Apriori and FP-Growth in terms of execution time and output.
- Observed that FP-Growth achieved faster execution while producing the same frequent itemsets as Apriori.
- Evaluated the impact of different minimum support and confidence values on the number of generated rules.

## Conclusion

This project demonstrates the complete workflow of Market Basket Analysis using Association Rule Mining techniques. The implementation highlights how frequent itemsets and association rules can reveal customer purchasing behavior while comparing the efficiency of Apriori and FP-Growth for transactional data analysis.
