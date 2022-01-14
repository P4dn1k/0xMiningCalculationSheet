# 0xMiningCalculationSheet
Hey Miner,

This is a calculation sheet to track your profits and costs for your mining operation.
I'am developing this sheet actually since 2017, as I was mining from 2017 till 2019 and than came back again to the mining community in 2021.							
Since then this Sheet has gone trough a lot of changes, updates and iterrations, but just now i feel that this could be a solid framework which can be build on further.
Feel free to use, copy, develop, change the sheet as you wish.

https://docs.google.com/spreadsheets/d/15RaMFzUHaoNgwgHiAK74CFbqax0wmZXLp9Ub3znIfWA/edit?usp=sharing

I would be very thankful for your donations!

BTC: bc1qu4vukxrhpp6hr8h853ugtzgkyh2a2uaud6qpr8

ETH (ERC20 or Polygon): 0x84B751981c027922937D2f60614c32f5Dcd284b3


How to use it?

![1](https://user-images.githubusercontent.com/80412388/149425924-d07f5976-26b5-4003-8ada-937fcba4dc02.png)

The sheet consists of two types of cells:
1st Type of cell is the one you fill out your data manually (Brighter grey).
2nd Type of cell is that one which are some calculations are made and you dont need to fill out anyting manually (Darker grey). 

This calculations will be made automatically as soon as you pull the cell i.e:

https://user-images.githubusercontent.com/80412388/149432117-b29ece85-3469-46d7-acce-30d50cccf2e9.mp4



You can add pools to the right side of the sheet, they will automatically fill all the other sheets if you pull them.

https://user-images.githubusercontent.com/80412388/149435547-3a89daaa-0fad-44b3-8eec-26d70fb2a6ac.mp4



This sheet can also calculate multiple coins, but you need to add the conversion rate yourself from the Dataset sheet.

https://user-images.githubusercontent.com/80412388/149433188-e9d48f43-874b-4bfa-98c4-40bc5d60c319.mp4



Each gray box in the Dayli_Profit sheet represents a month, so make sure you stay in that range, otherwise the calculations in the further sheets wont be correct.

https://user-images.githubusercontent.com/80412388/149436187-b037b851-5211-4eee-87f6-6afcebfc1a6e.mp4


Sheet Backend Explained:

The Dayli_Profit Sheet is the main driver of the sheet where all data are collected for the other sheets.
Monthly_Profit is sumarising the data from the Daily_Profit Sheet.
Average/Day is pulling Average values from the Daily_Profit Sheet.
Pending Pool Payouts is showing how much have you mined into the pool till the payout threshold is met. You need to enter the payout threshold manually.
In Pool_Payouts you will enter the Payouts the pool made to your wallet.
Dataset is the Backend of the sheet, where conversion rates can be found and the electricity cost.
Please edit the sheet to the corresponding rates of your local currency.

