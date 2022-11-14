Combining data sets
Task 1
import orders_wrangled.csv, order_products_prior.csv(new dataset)
merge datasets on order_id
export as orders_products_prior_combined.pkl (pickle file)

Task 2
import orders_products_prior_combined.pkl, products_wrangled.csv
merge datasets on product_id
export as orders_products_combined.pkl