# 📖 Data Dictionary

## ev_sales_clean.csv

| Column | Type | Description | Example |
|---|---|---|---|
| year | integer | Calendar year | 2022 |
| country | string | Country name | China |
| region | string | Geographic region | Asia Pacific |
| ev_sales | integer | Number of EVs sold that year | 4800000 |
| total_car_sales | integer | Total cars sold (EV + ICE) | 18200000 |
| ev_share_pct | float | EV as % of total sales | 26.4 |
| policy_incentive | boolean | Whether gov. incentive existed | TRUE |

## commodity_prices_clean.csv

| Column | Type | Description | Example |
|---|---|---|---|
| year | integer | Calendar year | 2022 |
| month | integer | Month (1–12) | 6 |
| steel_ppi | float | Steel Producer Price Index | 312.4 |
| copper_usd_per_ton | float | Copper price USD/tonne | 9450.0 |
| cement_ppi | float | Cement Producer Price Index | 198.7 |
| steel_pct_change_yoy | float | Year-over-year % change in steel | 18.3 |
| copper_pct_change_yoy | float | Year-over-year % change in copper | 24.1 |
