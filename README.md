执行代码中的提示

```
Welcome to the Marketplace
Are you a Customer or a Seller?
customer
Please enter your username
dy
Would you like to see all products, filter/sort products, or view your history?
1. View all
2. Filter/Sort
3. View history
4. View stats dashboard
5. Using shopping cart
5
Products for sale now

New Product: b
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 5

New Product: a
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 5
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
3
 Whether to continue adding, 1. Continue 2. Exit add 
1
 Enter product name 
a
 Input quantity 
1111
 Whether to continue adding, 1. Continue 2. Exit add 
2
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
1

New Product: a
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 1111
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
5
not success
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
1

New Product: a
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 1111
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
2
 Enter product name 
a
 Input quantity 
1
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
1

New Product: a
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 1110
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
5
not success
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
4

Process complete.
Thank you for using the Purdue Marketplace!
Have a good day!
```

执行完之后，会保存该名字顾客的购物车内容，以便该顾客再次登录的时候可以使用。这个是写在购物车内容的要求。上面“dy”顾客，选择了商品a并且要了1110个数量在购物车。

文件内容（dy.csv）如下，

```
a,ss ss,eeee,2.00,1110

```

再次运行程序，程序读取上次购物车的内容了，并且最后改到相应的数量就可以购买了。

```
Welcome to the Marketplace
Are you a Customer or a Seller?
customer
Please enter your username
dy
Would you like to see all products, filter/sort products, or view your history?
1. View all
2. Filter/Sort
3. View history
4. View stats dashboard
5. Using shopping cart
5
Products for sale now

New Product: b
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 5

New Product: a
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 5
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
1

New Product: a
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 1110
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
5
not success
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
2
 Enter product name 
a

 Input quantity 
1105
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
1

New Product: a
Store name: ss ss
Description: eeee
Price: 2.00
Quantity: 5
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
5
success
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
1
empty cart
1. view cart products 
2. Delete cart products 
3. add product 
4. Exit
5. purchase
4

Process complete.
Thank you for using the Purdue Marketplace!
Have a good day!

```

