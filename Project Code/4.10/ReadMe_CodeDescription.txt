Part 1
import orders_products_customers_combined.pkl
create column region based on state, labels are: northeast, midwest, south, west
create more_than_5_orders flag
create 2 dfs, morethan5 and lessthan5
create column parents based on num_dpdnts, label 0 or 1
create column economic_class based on income, labels: lower, middle, upper
create column age_group based on age, labels: young adult, adult, middle aged, senior
create column pets_flag based on department_id of 8, label 0 or 1
create column bulk_flag based on department_id of 10, label 0 or 1
create column baby_flag based on department_id of 18, label 0 or 1
vis based on new columns
import departments, merge to get department names
vis for departments
export visuals
export as FinalDataFrame.pkl, FinalDataFrame_MoreThan5.pkl, FinalDataFram_LessThan5.pkl

Part 2
Creates a dataset for demographic analysis
One row per user_id
Creates visuals for final report
exports FinalDataFrame_MoreThan5_DistinctUser.pkl
