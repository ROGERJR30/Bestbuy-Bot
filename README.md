# BestBuy Bot for Graphic Card | Open Source 
```
Please star my repo if this contribution helped you ! Its FREEE !
```


![logo](bb_kk.png)

## Description

BestBuy Bot is an Add to cart and Auto Checkout Bot. This auto buying bot can search the item repeatedly on the collection page using keywords. Once the desired item is available it can add to cart and checkout very fast. This auto purchasing BestBuy Bot can work on Chrome Browser so it can run in all Operating Systems. It can run be in multiple chrome profiles too to run for multiple items simultaneously.

“Buying a bot can increase your success chances only but no guarantee that you will successfully cart each time. If you do not agree, then please do not use this code.”

```
#AddToCartBot #AutoCheckoutBot #MABBots #AdvancedBots #AutoBuyingBot #AutoPurchasingBot #MostAdvancedBots #BestBuyBot
```

## Getting Started

1. Create a [github](https://github.com/login?return_to=%2Fkkapuria3) account. It always helps !
2. Star this repository. Its FREE !
3. Please follow me here if you like my contribution: [<img src="https://p.kindpng.com/picc/s/726-7262336_deadpool-logo-pixel-art-hd-png-download.png" width="25"/>](https://github.com/kkapuria3)

### Dependencies


1. [Tampermonkey Extention](https://www.tampermonkey.net/)
2. BestBuy Account (Please be signed in, Save your address, Save your creditcard) 


### Installing

* Go to tampermonkey dashboard from broswer extension. 
* Create a new script and copy the script from 'best-buy-tm.js'.
* Save the script
* Change required parameters* (Important)



### Executing program

* Once the script is saved please update the following variables:
* Item Keyword corresponds to a keyword in your product name (no spaces allowed)
```
var ITEM_KEYWORD= "3060";
```
* Credit Card CVV (requires card to be saved)
```
var CREDITCARD_CVV = "***";
```
* ```TESTMODE = 1``` will not purchase item. But do all the steps except pressing the last button. ```TESTMODE = 0 will``` purchase the item.



## Workflow

This tool is designed to multitask. That means, it can run in many tabs simultaneously, if there is a ```ITEM_KEYWORD``` overlap.
If there is no ```ITEM_KEYWORD``` overlap. You will need to create a new copy of script for each ```ITEM_KEYWORD```.

Please make sure your CART is empty.

After updating variables and enabling the script in Tampermonkey, go to the your favourite GPU page in BestBuy.
If the Title of GPU has ```ITEM_KEYWORD```, it will add the item to cart and checkout. If item is out of stock it will keep on refreshing every 5 seconds.

Please use ```TESTMODE = 1``` to test with an item already in stock.

## Authors

* KK


## Version History


* 1.0
    * Initial Release 

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
