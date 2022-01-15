# 0xMiningCalculationSheet
Hey Miner,
This is a calculation sheet to track your profits and costs for your mining operation. 
I'am developing this sheet actually since 2017, as I was mining from 2017 till 2019 and than came back again to the mining community in 2021. Since then this Sheet has gone trough a lot of changes, updates and iterations, but just now i feel that this could be a solid framework which can be build on further. 
Feel free to use, copy, develop, change the sheet as you wish.

https://docs.google.com/spreadsheets/d/15RaMFzUHaoNgwgHiAK74CFbqax0wmZXLp9Ub3znIfWA/edit?usp=sharing

How to use it?

The sheet consists of two types of cells: 

1st Type of cell is the one you fill out your data manually (Brighter grey). 

2nd Type of cell is that one which are some calculations are made and you don't need to fill out anything manually (Darker grey).
![1](https://user-images.githubusercontent.com/80412388/149536042-e0e5fa39-a9e8-44a0-91b1-06f9c7e65a51.png)



This calculations will be made automatically as soon as you pull the cell, here's an guide on how to use the sheet on an example of flexpool.io:

https://user-images.githubusercontent.com/80412388/149542576-590795b5-0ac9-44cb-9154-2988342b31ce.mp4





You can add pools to the right side of the sheet, they will automatically fill all the other sheets if you pull them.

https://user-images.githubusercontent.com/80412388/149542665-d4e638fa-0988-4775-91b7-b07ee90d5710.mp4



This sheet can also calculate multiple coins, but you need to add the conversion rate yourself from the Dataset sheet.

https://user-images.githubusercontent.com/80412388/149542714-fc290223-7cf3-41e1-bd94-f783949829d2.mp4





Each gray box in the Dayli_Profit sheet represents a month, so make sure you stay in that range, otherwise the calculations in the further sheets wont be correct.

https://user-images.githubusercontent.com/80412388/149542754-d5315f21-599a-4c71-aa81-c05d54351c4b.mp4





Sheet Backend Explained:
The Dayli_Profit Sheet is the main driver of the sheet where all data are collected for the other sheets. Monthly_Profit is sumarising the data from the Daily_Profit Sheet. 

Average/Day is pulling Average values from the Daily_Profit Sheet. 
Pending Pool Payouts is showing how much have you mined into the pool till the payout threshold is met. You need to enter the payout threshold manually.

In Pool_Payouts you will enter the Payouts the pool made to your wallet. 

Dataset is the Backend of the sheet, where conversion rates can be found and the electricity cost. 

Please edit the sheet to the corresponding rates of your local currency.

If you have any questions, I am glad to help, or you could also pull a request on my github.

Happy Mining!

Donations:

BTC: bc1qu4vukxrhpp6hr8h853ugtzgkyh2a2uaud6qpr8

ETH (ERC20 or Polygon): 0x84B751981c027922937D2f60614c32f5Dcd284b3
