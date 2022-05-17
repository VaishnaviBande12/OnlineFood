# Food Ordering System


Note -
---------
1. This is not ready for PRODUCTION.
2. The username and password of sample users are stored in table `users`.
3. Only Customers with "Verified" status can place orders using "Cash on Delivery" option.
4. By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
5. Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
