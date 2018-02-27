# myShoppingCart
Simple shopping cart, created with Node.js, Mongodb, Expressjs, and AngularJs (MEAN
Currently, this project support 2 types of users: Admin and normal user.
Admin login: long, pass: 123. 
User login: longha , pass: 123.
Can register new user - but it will be normal user only. 
*********************************************************************************
Normal user can do the following:(longha, 123)
1. Add products available to cart - click on each header will sort that header.
2. View Cart and check out, or go back shopping. 
3. Can remove items in the cart.
4. Submit order will display a confirmation number.
5. User can click on user Account to see Past Order. Click on order number to see the items & quantity purchased for each order.

Admin user can do the following:(long, 123)
1. First page displayed will allow admin either to see: Products, Orders, or Users
2. Products --> Features include: Add new product, edit, update, and delete. Add new product will show a form for admin to add new product. After save new product will take admin back to the Products table. Click on Edit - The update button will change color -- indicating that the row is currently editable. Click update will update product in that row and make the row uneditable again. Delete will delete product in that row from the database.
3. Orders -- show current orders - the column header when click on will sort table by that column.
4. Users -->Show the list of current user. View a particular user will show past order belong to that user. Right now I allow changes to be made on Order Total, and Order Status. Click update will update that order on database. Click Delete will delete that order on 2 places: on Order database and on User.PastOrders array.


























** Features that I want to include with next update:
* Change password for user
* Admin can change normal user to admin role
* More styling
* When remove items from cart, this should increase the available quantity of product removed from cart
* Add some features to Admin page, like Save all on product table, be able to edit Order table, etc.
* Secure database by only return relevant infor about user - but not sending back password.

