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
   5. Regarding emergency support
      - In a case of an emergency need of support, customers can search for service centres nearest to their locations and send service requests to those centres (availability of servicemen (will be updated by the service centre as they assign servicemen) will be displayed to the customer with service centres details so that he/she can make a choice of who to contact)
      - Customer receives contact info of the employee who's assigned to his/her emergency request if the service center accepts service request.

## Administrator

This user role is managing the whole system and used by the company who will be maintaining this system.To access the admin portal, user must always be authenticated to prove he/she has admin access.

1. Regarding authentication  
    - Login to the admin portal
    - Logout from the admin portal
    - reset/change password
2. Regarding service centres
    - Upon receiving registration requests from service centre businesses(these will include details and document), Administrator can check & verify them and create an account for them in the system and provide that business with the credentials to their dashboard.
    - when a business requests for a update in their details, admin can verify them and do the necessary change for them. (Service centres shouldn't be able to do it directly because as a business, their details should be stable and only changed by admin if they can verify that new details are correct).
    - see the ratings received by service centres to see if there are any problems (eg: if a centre receives bad reviews constantly)
    - see complaints and suggestions sent by service centres.
3. Regarding Spare parts sellers