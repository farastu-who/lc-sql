## Solutions

1757. Recyclable and Low Fat Products 
      Link - https://leetcode.com/problems/recyclable-and-low-fat-products/description/?envType=study-plan-v2&envId=top-sql-50

      Solution -
      # Write your MySQL query statement below
    SELECT product_id
    FROM Products
    WHERE low_fats = 'Y' AND recyclable = 'Y'

584. Find Customer Referee
     Link - https://leetcode.com/problems/find-customer-referee/description/

     Solution -
     # Write your MySQL query statement below
    SELECT name
    FROM Customer
    WHERE referee_id != 2 OR referee_id IS NULL