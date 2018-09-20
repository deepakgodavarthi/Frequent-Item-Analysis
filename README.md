# Frequent-Item-Analysis

We will perform frequent item analysis on the Instacart Market Basket dataset. For
simplicity, we will only use two files \order products train.csv.zip" which contains the transaction
data, and the \products.csv.zip" file which contains details of the product.

Below are the steps of the project:

1. Load dataset using the path specified in the first argument to the class.

2. Create Transactions from the dataset. You only need two fields: \order id" and \product id".

Each order id represents one transaction.

3. Create FPGrowth model. You can see an example here: https://spark.apache.org/docs/
latest/mllib-frequent-pattern-mining.html. You are free to choose an appropriate value
for the support parameter.

4. Find Frequent Itemsets: Write the top 10 most frequent output to a file specified by the
output argument.

5. Generate Association Rules: You will the model.generateAssociationRules method to gen-
erate high-confidence association rules. You are free to choose the confidence threshold value.

You will output the top 10 rules with the highest confidence values to the same file as step 4
above.

Remember to write your code in the form of a Scala class with two input arguments- location of input
file, and location of output.
