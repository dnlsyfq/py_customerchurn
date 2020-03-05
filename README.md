#Customer Analysis

---
**Customer Segmentation**

Segregating customers using criteria like :
* Age Bracket
* Gender
* Geographic
* Demographic - Race, Religion etc
* Item Purchased
* Buying Freq
* so on

---

**Objective**:
* To determine which segments would increase sales
* Optimising targetted Ads

---

**Modelling:**
Find ranking mechanicsm to determine best criteria for chosen segment

1. **Feature Scaling : Min Max Normalization**

* Normalize the *Amount Spent* and *No. of Purchase*

$$ x` = \frac{x - min(x)}{max(x) - min(x)}$$ 

2. **Scoring Model : Weighted Sum**
* To rank customers takes two criteria : *Amount Spent* and *No. of Purchase*

* *Define the score of a customer :*

$$(\frac{1}{2} * {No. of Purchase}) + (\frac{1}{2} * {Amount Spent})$$ 




---