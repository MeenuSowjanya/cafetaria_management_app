# Hello!🖐 & Welome to [A Cup of Joy]()

### To get complete eperience of the platform visit *_[ACupOfJoy.com]()_* and login via *admin* role

| Name | Email | Password | Role |
|----  |  -----|  ------- |----  |
| admin | admin@email.com | admin | admin |
| customer | customer@email.com | customer | customer |
| Billing Staff | billing@email.com | bill | billing staff |

I am Meenu Sowjanya and this is my project , a Cafeteria Management System built on Rails which supports multiple users and roles like admin, customer, and billing-clerk.

Here different Users get different views of the application, depending upon the roles assigned to them : [ "admin" , "customer" , "billing clerk "].

> There are three personas in this Cafeteria system:

- Cafeteria Owner: The owner has complete access of the system. They can add and update stock, create invoices, see all reports, mark orders as delivered and so on.
- Online Customer: A customer can place an order online and can see a menu from which they can place an order. They can also see the invoice details and status of their order, but they do not see anything else about the system.
- Cafeteria Billing Clerk: The billing clerk is the person taking customer orders directly from the counter. They can create new invoices, print them, and see order status. However they are not be able to modify item details or see reports like income since they sholud be only seen by the owner.

## More Insights into the different personas

### Customer

- Customer are able to Sign-up
- Customer can see the menu and add items to cart
- Customer can see the cart while ordering

### Cafeteria Billing Clerk

Billing clerks can only sign-in and sign-out. They cannot sign-up by themselves. Their accounts are created only by the owner.

- Clerk can mark orders as delivered : They can see the list of all pending orders from the queue of orders. They can also mark orders as “delivered”.
- Clerk can create orders for offline customers.

### Cafeteria Owner

Nobody can sign-up as an owner. Instead, the live application comes with an owner already created. An owner can create other owners.

- Owner can manage the menu
- Owner can see reports such as : Sale Reports for any given date range , see details of a single invoice , apply filter on orders to list orders during a particular time period.
- Owner can manage users : They can see the list of all users - customers, billing-clerks, and other owners.
- They can create and update billing clerks and owners.

