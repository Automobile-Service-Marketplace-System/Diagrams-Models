# User roles and their functionalities

## Customer

Mainly two types of customers,

1. Unauthenticated customers (either don't have an account or not logged in)
2. Authenticated customers (customers who has an account and currently logged in)

Some features are only available to customers who have accounts.

1. Features available to all customers

   1. Regarding authentication
      - Customer can create an account
      - customer can login to the account
      - forget password feature (customer can reset password if forgotten by entering correct email)
   2. Regarding spare parts
      - search for spare parts
      - filter spare parts based on their preference (based on factors like type, condition)
      - visit shops's page and see details(their other products, contact details etc)
   3. Regarding accessories
      - search for accessories/modifications
      - filter accessories based on preferences
      - visit shops's page and see details(their other products, contact details etc)
   4. Regarding auto-mobile services & repairs
      - Search for services and service centres which offer them
      - filter them according to categories (full services,hybrid services, car wash, repairs etc.)
      - see customer reviews for these service centres
      - visit shops's page and see details(other services they provide, contact details etc)
      - search for nearby locations

2. Features only available for authenticated customers

   Apart from above features, authenticated users will get these extra features,

   1. Regarding authentication
      - customer can change account details (address, phone number etc)
      - reset password
      - logout from the system
   2. Regarding spare parts
      - reserve spare parts from a shop they prefer (for a small fee)
      - cancel reservations (reserve fee wil not be refunded)
   3. Regarding accessories
      - post accessories reviews and see other customer reviews
      - <span style="text-decoration: line-through">add accessories to a cart</span><sup>1</sup>
      - <span style="text-decoration: line-through">place orders in the cart or individual accessories (several payment methods, payments will be directed to seller accounts)</span><sup>1</sup>
      - <span style="text-decoration: line-through">see the order status</span><sup>1</sup>
      - <span style="text-decoration: line-through">see past orders/payment history</span><sup>1</sup>
   4. Regarding auto-mobile services & repairs
      - Post reviews for services of service centres
      - make appointments for services
      - cancel appointments or update appointments
      - receive confirmations for appointments
      - see their appointments & service history
      - set reminders for scheduled vehicle servicing
      - see the progress / status for repairs
   5. Regarding emergency support / roadside assistance
      - In a case of an emergency need of support, customers can search for service centres nearest to their locations and send service requests to those centres (availability of servicemen (will be updated by the service centre as they assign servicemen) will be displayed to the customer with service centres details so that he/she can make a choice of who to contact)
      - Customer receives contact info of the employee who's assigned to his/her emergency request if the service center accepts service request.

## Administrator

This user role is managing the whole system and used by the company who will be maintaining this system.To access the admin portal, user must always be authenticated to prove he/she has admin access.

1. Regarding authentication
   - Login to the admin portal
   - Logout from the admin portal
   - reset/change password
   - forget password feature (admin accounts can reset password if forgotten by entering correct email)
2. Regarding service centres
   - Upon receiving registration requests from service centre businesses(these will include details and documents), Administrator can check & verify them and create an account for them in the system and provide that business with the credentials to their dashboard.
   - when a business requests for a update in their details, admin can verify them and do the necessary change for them. (Service centres shouldn't be able to do it directly because as a business, their details should be stable and only changed by admin if they can verify that new details are correct).
   - see the ratings received by service centres to see if there are any problems (eg: if a centre receives bad reviews constantly)
   - see complaints and suggestions sent by service centres.
3. Regarding Spare parts sellers

   - same as service centres, admin should be able to create new accounts for them after verifying details
   - same as service centres, admin can update details of spare part sellers after verifying details
   - same as service centres, admins can see use ratings to determine issues with sellers
   - same as service centres, admin can see complaints and suggestions by spare part sellers.

4. Regarding customers
   - **Has to inquire madam about hwo to incorporate customer care to the system (Should admin accounts be the ones that can reply to users or should we also have another user role such as "Support staff") ?**

## Service Center

Service center is an actor that provides various service such as,

1.  Repairing
2.  Car wash
3.  Full service
4.  Hybrid service
5.  paint jobs
6.  Roadside assistance in emergency situations etc.

Not all service centres provide all these services but a service centre provides at least one service.There are two states for these user role,
A service center account provides them with a sort of a their own dedicated
page to showcase the services they provide and their other info(contact, address etc.)

1. Unauthenticated users (either logged out or doesn't have an account yet)
2. Authenticated users (logged in users)

Almost all of the features are only available to authenticated users.

1. Features of Unauthenticated users.
   1. Regrading authentication
      - Request to create a service center account by filling out details and providing required documents.Will receive confirmation via email after an admin verifies the details and creates an account for them.
      - Login to and already existing service center account
      - Forgot password feature forget password feature (Service centres can reset password if forgotten by entering correct email)
2. Features of authenticated users.

   1. Regarding authentication
      - Log out from the service centre dashboard
      - Reset password

   2. Regarding service center info & services
      - Request admin to change business info by providing necessary details and documents.
      - view/enter/update/delete details about services they provide .These changes will be reflected on their dedicated pages
      - add/edit/delete customized banner image for dedicated pages
        (along with some minor customization)

   3. Regarding support
      - can inquire admins about issues they face using the platform

   4. Regarding customers
      - accept/reject service appointments
      - see reviews posted by customers for the service center.

   5. Regarding spare-part selling

      Since service centers also can sell spare parts, there are features surrounding it too

      - add new spare parts to the catalogue
      - update details of existing spare parts
      - delete spare-parts from catalogue
      - see reservations of spare parts from customers
      - after selling the reserved parts, clear reservations.
      - see analytics about sale performance

   6. Regarding accessories  

      Since service centers also can sell accessories, there are features surrounding it too

      - add new accessories to the catalogue 
      - update details of existing accessories 
      - delete accessories from catalogue 
      - see analytics
      - **If we implement a ordering method for customers to pay and order, features like, see unfulfilled orders, mar them a fulfilled after sending the product to customer, past orders and view selling performance**

   7. Regarding emergency support / roadside assistance
      - admins receive emergency requests from customers with a location attached.
      - if it's possible to assist that customer, admin can accept and send contact details of the technician sent for him.
      - If it's longtime repair then the admin will update the progress to the system.
      - etc.
   8. Regarding reparing

      - maintain staff can update the current status and progress of the vehical. and it will be easy for customers to keep in touch
      - after reparing, service center can send messege/notification to customer regarding when can they get their vehical and other details
      -see the vehical service history to analyze problems and changed parts.

## Spare-part Center
Spare-parts are sold via spare-part Shops and also service centers can sell spare-parts as a service. 
1. Regarding spare-part shop
    - Login to the system if there is a already created account otherwise create a new account providing required information to the administrator 
    - Forget password feature (Spare-parts centres can reset password if forgotten by entering correct email)
    - add/update/delete spare-parts
    - see the reserved spare-parts and reserve for the customer if it's possible
    - Notify customer when the order is ready
    - Contact customer for further clarification 
    - etc.
2. Regarding spare-parts where sell in the service centers
    - add/update/delete spare-parts
    - see the reserved spare-parts and reserve for the customer if it's possible
    - Notify customer when the order is ready
    - Contact customer for further clarification 
    - etc.



   

   
