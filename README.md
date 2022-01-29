# Tampermonkey Coinbase Rewards Tool for Cointracker.io
## About
Since Cointracker does not currently support bulk editing of transactions, this tool allows you to automatically mark all 'Coinbase Rewards' transactions as 'Staked'. It identifies all transactions that contain the message 'reward<br>From Coinbase' and selects the 'Mark as staking reward' option, if not already selected.

## How it works.
When you visit any 'Transactions' page, this button is added to the page.
</br></br>
![image](https://user-images.githubusercontent.com/7255687/151669048-17db449a-7184-4b0c-9f02-b3b2974f83fb.png)

When you click the button, it will ask if you would like to run it for all pages.
</br></br>
![image](https://user-images.githubusercontent.com/7255687/151669129-2772d9a9-c103-4c2d-95d0-3dd5165ec74d.png)

If you select 'ok' it will automatically mark all 'Coinbase Rewards' transactions on the page as 'Staked' and then automatically navigate to the next page until all 'Coinbase Rewards' transactions on all pages are updated.

If you select 'cancel', it will also mark all relevent transaction on the page except it will confirm if you would like to continue to the next page or not.
</br></br>
![image](https://user-images.githubusercontent.com/7255687/151669246-16a1d740-9b95-4551-b442-8bdb50ed7407.png)

After all 'Coinbase Rewards' transactions are updated on all pages, it will let you know.
![image](https://user-images.githubusercontent.com/7255687/151669306-e80a9f60-fe11-45c7-aee3-1ac6a561e225.png)
