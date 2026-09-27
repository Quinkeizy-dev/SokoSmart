#Data Source
Dataset name: Retail Store Inventory and Demand Forecasting. 
Source URL: https://www.kaggle.com/datasets/atomicd/retail-store-inventory-and-demand-forecasting. 
Downloaded on: 9/27/2026.
File used: sales_data.csv.

 why I picked this dataset 
 it includes inventory level, units sold, and units ordered together, which matches what SokoSmart needs for both forecasting AND the reorder-logic phase later. 
 Its known limitation 
 it's synthetic data, not real Kenyan vendor data, so it won't reflect Nairobi-specific patterns like school-term or payday demand spikes described in my Appendix B observations.


Note;
I filtered the dataset to Category == 'Clothing' only, to match SokoSmart's fashion-vendor focus, since the raw file also contains Electronics, Groceries, Toys, and Furniture which are out of scope.