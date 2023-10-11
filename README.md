# Company Sales Analysis

We want to conduct an analysis on the product sales of a company and obtain information about it's various retailer types expressed in offset from UTC.
We will also display the total and average amount of sales that occured in each time zone.

***

# The Dataset

The dataset contains real estate values showing product sales of a globally operating company over a certain period of time.
It contains 100 entries showing sales id, country, revenue in $, date of sale, time of sale and time zone.

***

# Process Steps

1. Data Preparation

    - Store the date and time values in a single column called "MOS", denoting "Moment of Sale". Verify that the time zone values stored in "sales_data" are valid and can be manipulated with the pytz module.

2. Data Manipulation

    - Estimate the offset of the values of "MOS" to UTC. Store them in a column called "OffsetUTC".

3. Data Analysis

    - Order all sales according to a reconciled UTC-equivalent of the moment of sale and analyze the data.

4. Data Visualization

    - Obtain statistics and visualizations of our data.

