# Smart Shopping Cart | HackFest 19 | Walmart 🛒---<img src="https://github.com/HeliosX7/Walmart-Smart-Shopping-Cart/blob/master/images/intro.jpg" style="float:center;" width="500">`Team Name : HORIZON`               ---## Problem OverviewIn the present scenario, it has been observed that after shopping in malls or any such place,  customers waste a lot of time at the counter in the queue waiting for there turn of bill processing. We aim at designing the best substitute for the counter that could substitute and drastically reduce the time spent at the billing counters.---## Solution OverviewOur approach involves combining IOT and Android to offer a seamless shopping experience :* Each Smart Cart  has an in-built Raspberry Pi and Camera to detect the barcode associated with a product.* PIR and Weight sensors are also attached to the Cart to facilitate an anti-thievery mechanism.* While, an Android app is also provided for payment and self-checkout.---## Workflow & Components<img src="https://github.com/HeliosX7/Walmart-Smart-Shopping-Cart/blob/master/images/workflow.jpg" align="middle">***<img src="https://github.com/HeliosX7/Walmart-Smart-Shopping-Cart/blob/master/images/hardware.jpg" align="middle">* **Camera** :Captures the video feed and sends it to the Raspberry Pi for further processing.* **Raspberry Pi** :Processes the video feed, decodes the barcode and sends the bill to the database.* **PIR sensor** :Prevents thievery from ‘NO’ section after the checkout.* **Load sensor** :Verifies the weights of the scanned products.* **YES / NO Sections in Cart** :Our shopping cart consist of user friendly cart with two sections – namely YES section and a NO section. This feature has been incorporated so as to make the life of customers easier. Items which are confirmed to be bought are placed in YES section while the items which are not confirmed to be bought are placed in NO section. ***<img src="https://github.com/HeliosX7/Walmart-Smart-Shopping-Cart/blob/master/images/android_snippet.jpg" align="middle">---## Estimated Cost| Item                         | Price (₹)     | |:----------------------------:|:-------------:| | Raspberry pi                 | 2000          | | Raspberry pi camera (5 mp)   | 700           |  | Load sensor and load cell    | 600           |  | PIR SENSOR                   | 300           | | ATMEGA 328p MICROCONTROLLER  | 100           |  | **`Total`**                  | **`3700`**    |  > “BUT THE COST CAN BE REDUCED BY THREE FOLDS IF  WE DESIGN THE MICRO-CONTROLLER WITH SPECIFIC FEATURES NEEDED FOR DESIGNING THE SMART CART”---## Snippets<img src="https://github.com/HeliosX7/Walmart-Smart-Shopping-Cart/blob/master/images/hackfest_snippet.jpg" align="middle">---## ConclusionThis smart cart will help the customers drastically reduce their waiting time in the queue through it’s self checkout facility. It is also a cost-effective solution to this problem. We have focused on providing a seamless shopping experience using a interactive Android UI and adding a ‘NO’ section for doubtful products. Anti-Thievery was also taken into account and a few measures to prevent this were also deployed.