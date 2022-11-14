This code is checking data consistency in Python
import orders_wrangled.csv, products.csv
Products.csv
	remove nulls
	drop duplicate rows
	export clean data
orders.csv
	check for dups
	check for mixed data types
	check for nulls (nulls in days_since_prior_order)
		create flag for nulls (nulls probably mean user only has 1 order)
	export