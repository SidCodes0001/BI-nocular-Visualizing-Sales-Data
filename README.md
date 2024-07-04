# BI-nocular Visualizing Sales Data

## Introduction
This dashboard helps the management understand their data better.  Analyzing different charts, they get to know their improvement area, & thus they can improve their services by identifying these area. 



#### Here are some of the key points I noticed

- There is a good profit in month of **March** , so management can analyze in backend what was the reason behind it and replicate techniques for future.
- Average delivery time was very high. New measure was created to to get this data (we calculated the difference b/w order date and shipping date). Following DAX expression was written for the same,
        
        DeliveryTime = DATEDIFF('Sheet1'[Order Date],'Sheet1'[Ship Date],DAY)
    

- Most of the business is centered towards **West** , sales numbers clearly justifies it.

- Profits in **Central** area were flat negative.

- **Seattle** was best city in terms of profit w.r.t sales . 

- Almost **46% of deliveries** were done through **Standard Class**.

- Almost 42% of people prefer COD, followed by Online.

- **Copiers** contribute to almost 50% of the profits of the business.

- Office supplies contributes to most of the sales.
 
 

 

 
 


# Snapshot of Dashboard

![image](https://github.com/SidCodes0001/BI-nocular-Visualizing-Sales-Data/assets/64726248/0c7a2310-c621-4b1d-9578-b8f9670f58c1)

 





    
