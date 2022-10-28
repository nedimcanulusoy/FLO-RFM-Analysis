<div style="font-style: bold; text-align: center;" markdown="1">

## RFM Analysis of FLO Dataset

</div>

--- 

### Problem
FLO wants to put its customers into segments and determine marketing strategies 
according to these segments. Besides these, FLO also wants to define the behaviours 
of the customers and form groups according to the clusters in these behaviours.

---

### Dataset
The dataset consists of the information obtained from the past shopping behavior 
of customers who made their last purchases from Flo as OmniChannel (both online and 
offline shopper) between 2020 - 2021.

There are `12 different variables`, around `20 thousand observations` in the dataset.

`Variable list of the dataset:`

    master_id                          : Customer ID 
    order_channel                      : Channel of the purchase (Android, ios, Desktop, Mobile)
    last_order_channel                 : Last channel of the purchase  
    first_order_date                   : First purchase date of the customer
    last_order_date                    : Last purchase date of the customer
    last_order_date_online             : Last online purchase date
    last_order_date_offline            : Last offline purchase date
    order_num_total_ever_online        : Total number of online purchases made by the customer
    order_num_total_ever_offline       : Total number of offline purchases made by the customer
    customer_value_total_ever_offline  : Total amount of offline purchases paid by the customer 
    customer_value_total_ever_online   : Total amount of online purchases paid by the customer
    interested_in_categories_12        : List of categories the customer has shopped in the last 12 months

---

### Installation
1. Clone this repository

```
https://github.com/nedimcanulusoy/FLO-RFM-Analysis.git
```

2. Change directory to the cloned repository

```
cd FLO-RFM-Analysis
```

3. Open the notebook and run the cells

---

### Disclaimer

The data set is not included due to General Data Protection Regulation (GDPR) rules.

---