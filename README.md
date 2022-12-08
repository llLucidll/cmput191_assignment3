## RTX 4090 Index

The reason I picked the RTX 4090 as my commodity is because I wanted to build a PC using it as a component and figured this assignment would help me decide if I should source the GPU from Canada or if I should buy it when I go back home to the UAE for holiday

![RTX 4090](rtx_4090.jpg "RTX 4090")

Now to get pricing data from different countries, Nvidia isn't a central vendor like Apple is and a lot of the prices of the GPUs in different countries are decided by third party vendors and as such there is no pricing table you can scrape off their website. I resorted to pulling the price of the GPU off newegg while changing my country of residency manually. I found newegg the most reliable source as Amazon has people selling it for almost 3 times MRP in some countries.

![newegg](newegg.jpg "NEWEGG")

After converting all the prices from the local currencies to Canadian dollars using the CurrencyScoop API, and graphing the differences in price, somewhat of a pattern seemed to be present but there were a few outliers present that could not be explained namely the price in Canada being so high compared to the neighbor the US.


