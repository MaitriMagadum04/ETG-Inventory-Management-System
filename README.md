# ETG-Inventory-Management-System
JSON based inventory management system

**About Json Files:**

JSON (JavaScript Object Notation) is an open standard record configuration and information trade design that utilizes intelligible text to store and communicate information objects comprising of characteristic worth combines and exhibits (or other serializable qualities). It is a typical information design with an assorted scope of usefulness in information exchange including correspondence of web applications with workers. 

JSON is a language-autonomous information design. It was gotten from JavaScript, however numerous cutting edge programming dialects incorporate code to produce and parse JSON-design information. JSON filenames utilize the .json extension.

->record.json file holds the items which were present prior to any of the changes amde to the code.

->records.json file has the extra elements added by the user to the inventory.

->afterpurchase.json file holds the items quantity modified after a customer purchases a item from the inventory.

->sales.json file holds the Transaction details and the items left in the inventory.


**IMS.ipynb:-**

Here we are adding the items into the inventory asking the input from the user. (The key company for 1001-1014 items is [company] and the key company for 1015-1030 items is [Company]). the upadated inventory is stored in records.json.

**IMS purchasing products.ipynb:-**

Here the user can purchase the items from the inventory and the total billing amount is generated and displayed to the user in the form of bill. and the time is displayed at which the useer purchased the item.

After this the updated records file is stored in afterpurchase.json where the quantity of the items purchased is reduced. Then the items purchased is stored in sales.json file this file also contains the details of what is remining in inventory after purchasing a particular item.

**Features:-**

-->Adding new item to the exixting inventory.

-->update inventory according to upadated items.

-->customer can buy/purchase the items in the inventory.

-->generate a bill according to the quantity od item purchased.

-->displaying the time and date of the transaction.

**Future scope:-**

-->We can automate the inventory such that if any item whose quantity is '0' the message should be displayed as 'The item you requested for is not in stock, please pre-order' then the user has to enter the items required.

-->We can also delete the items that are not used extensively by the customers. We can also update the quantity of the item whose quantity is less but more in demand.

-->We can generate a copy of a bill and send it to the customers as invoice.
