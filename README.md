## Project Title: Association Rule Mining with Simulated Data

#### Project Overview:

Simulating basic transactional data and using association rules to uncover shopping patterns.

#### Content:
- Simulate Transaction Data
- Analyze with Apriori
- Generate Rules

#### 1. Simulate Transaction Data
- Creating at least 10 fake transactions in Python.
- Ensuring each transaction has 2–5 items selected from a pool products with 10 unique items.

#### 2. Analyze with Apriori
- Converting the data to one-hot encoded DataFrame.
- Using the Apriori algorithm to find frequent itemsets with a minimum support of 0.3

#### 3. Generate Rules
- Generate association rules with a minimum confidence threshold of 0.7.

#### 4. Briefly describing atleast 2 rules

##### Rule 1:

antecedents: (bhusu)

consequents: (rasmalai)

support: 0.3

confidence: 1.00

lift: 2.50

**Explanation:**

- antecedents (bhusu): this means that the rule is based on the purchase of 'bhusu'.

- consequents (rasmalai): this shows that when a customer buys 'bhusu', they are also likely to buy 'rasmalai'.

- support 0.3: This means that 30% of all transactions in the dataset include both 'bhusu' and 'rasmalai'.

- confidence 1.00: This value indicates that whenever 'bhusu' is bought, 'rasmalai' is purchased 100% of the time. Simply put, every time someone buys 'bhusu' they also buy 'rasmalai'

- lift 2.50: This value suggests that buying 'bhusu' increases the likelihood of buying 'rasmalai' by 125% compared to if there were bought independently.

**Meaning:**

If a customer buys bhusu, we are very confident that they will also buy rasmalai. This may suggest that they like spicy-sweet food.

##### Rule 2:

antecedents: (ladoo)

consequents: (chevdo)

support: 0.3

confidence: 0.75

lift: 1.25

**Explanation:**

- antecedents (ladoo): this means that the rule is based on the purchase of 'ladoo'.

- consequents (chevdo): this shows that when a customer buys 'ladoo', they are also likely to buy 'chevdo'.

- support 0.3: This means that 30% of all transactions in the dataset include both 'ladoo' and 'chevdo'.

- confidence 0.75: This value indicates that whenever 'ladoo' is bought, 'chevdo' is purchased 75% of the time. Simply put, every time someone buys 'ladoo' they also buy 'chevdo'.

- lift 1.25: This value suggests that buying 'ladoo' increases the likelihood of buying 'chevdo' by 25% compared to if there were bought independently.

**Meaning:**

If a customer buys ladoo, we are very confident that they will also buy chevdo. This may suggest that they like sweet-spicy food.










