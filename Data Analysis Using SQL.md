Sales Insights Data Analysis Project

# Instructions to setup mysql on your local computer

    Follow step in this video to install mysql on your local computer [https://www.youtube.com/watch?v=WuBcTJnIuzo]

    SQL database dump is in db_dump.sql file above. Download db_dump.sql file to your local computer and import it as per instructions given in the tutorial video

# Data Analysis Using SQL

* Show all customer records

    <span style="color:gray">SELECT * FROM customers;</span>

* Show total number of customers

    <span style="color:gray">SELECT count(*) FROM customers;</span>

* Show transactions for Chennai market (market code for chennai is Mark001

    <span style="color:gray">SELECT * FROM transactions where market_code='Mark001';</span>

* Show distrinct product codes that were sold in chennai

    <span style="color:gray">SELECT distinct product_code FROM transactions where market_code='Mark001';</span>

* Show transactions where currency is US dollars

    <span style="color:gray">SELECT * from transactions where currency="USD";</span>

* Show transactions in 2020 join by date table

    <span style="color:gray">SELECT transactions.*, date.* FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020;</span>

* Show total revenue in year 2020,

    <span style="color:gray">SELECT SUM(transactions.sales_amount) FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020 and transactions.currency="INR\r" or transactions.currency="USD\r";</span>

* Show total revenue in year 2020, January Month,

    <span style="color:gray">SELECT SUM(transactions.sales_amount) FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020 and and date.month_name="January" and (transactions.currency="INR\r" or transactions.currency="USD\r");</span>

* Show total revenue in year 2020 in Chennai

    <span style="color:gray">SELECT SUM(transactions.sales_amount) FROM transactions INNER JOIN date ON transactions.order_date=date.date where date.year=2020 and transactions.market_code="Mark001";</span>

* To check for NULL entries 

    <span style="color:gray">SELECT * FROM sales.transactions WHERE market_code IS NULL;</span>
