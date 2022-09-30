# International Debt Statistics - PPG Bilateral Debt

## Objective

If you have been following new recently, you may have come across various headlines like "South Asia in Chinese Debt Trap", "Economic crisis in Sri Lanka", "Failing economy of Pakistan", etc. These news articles made me curious to look into bilateral lendings between 2 countries. Using python, I developed a script to download PPG Bilateral Debt data between 2 countries using World Bank API.

My project collects data of PPG bilateral lending between India and its neighbouring countries which include Bangladesh, Bhutan, Sri Lanka, Nepal, Maldives & Myanmar. I have wrangled and analysed data from last 20 years of each country individually and visualized the data in form of excel dashboard for easy understanding of lending trend. Check out the [project report](https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Project%20Report.pdf)

## About the dataset

Dataset includes details of PPG Bilateral debt data between India & Bangladesh/Bhutan/Sri Lanka/Maldives/Myanmar/Nepal obtained using World Bank API. Each dataset contains 4 columns: 'Year': Year of debt, 'Debtor': Debtor country code,'Debt in US$': Amount of debt in US$, 'YoY Growth %': Year on year growth percentage of bilateral debt.
All 6 datasets are combined, cleaned, wrangled and analysed [here](https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Bilateral%20Debt%20Analysis.xlsx)
Data is gathered from World Bank website and considered as primary data.

## Guidelines to use the script:

1) Check the code of Debtor Country by using this [script](https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Python%20Scripts/Debtor%20Country%20Code%20Script.py) or directly download excel file containing 'Debtor Country Code' [here](https://github.com/indtheblacktiger/International-Debt-Statistics/raw/main/Country%20Code%20Data/Debtor%20Country%20Code.xlsx)
2) Check the code of Creditor Country by using this [script](https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Python%20Scripts/Creditor%20Country%20Code%20Script.py) or directly download excel file containing 'Creditor Country Code' [here](https://github.com/indtheblacktiger/International-Debt-Statistics/raw/main/Country%20Code%20Data/Creditor%20Country%20Code.xlsx)
3) Use the [PPG Bilateral Debt Script](https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Python%20Scripts/PPG%20Bilateral%20Debt%20Script.ipynb) to save the required data in an Excel file.

## Conclusion of project

1) Total PPG Bilateral Lending has increased from less than 500 million $ in 2000 to about 45 billion $ in 2020
2) Bhutan has been the biggest debtor country receiving almost 18 billion $ over the period of 20 years
3) Nepal has received the least bilateral lending amounting to less than 1 billion $
4) Total bilateral lending show a positive growth rate since last 20 years
5) Total bilateral lending to neighbouring countries is approx. 1.2% of overall GDP of India 
6) In the event of default by any neighboring country in future, its impact on India’s financial sector will be minimal (Considering only the above data)
