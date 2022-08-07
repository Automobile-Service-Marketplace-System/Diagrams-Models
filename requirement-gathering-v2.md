# Vehicle service center & Auto parts shop management system

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
This system is for a fictional company (We researched and found that such companies exist in Sri Lanka(ex: Chamara Stickers, Grease Monkey)) which provides multiple services and also sells spare parts and other automobile accessories in their company.  
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;So a system for this company should have features to manage these services(service records, generate reports, handle repairs and services by providing required features in the multiple stages of such repairs/services.for example, for a typical full service, the system should implement features to handle vehicle admitting, generate fault reports and generate the bills).  
    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Also, the system should have features to manage the stock of spare parts, electronic parts, batteries, engine oil etc. And as this company also sells these auto parts online (for example grease monkey website allows to buy all kinds of vehicle parts and accessories online), there should be a customer-facing website where people can search for specific products, maintain a cart and order them, and these purchases should reflect on the system by correctly managing stock. This website also should double as the marketing website for the company.  
  
Based on these requirements, we've identified the following user roles.
    
1. Outside the company 
   - Customer  
    This is a normal user outside the company. Customers are the users of the company that provides services & products. These include vehicle repairs, vehicle servicing, selling spare parts & other products, modifications etc. A customer can have an account or not. Having an account gives more features to the customer (ex: a profile page where they can track their previous purchases, service history etc).

2. Inside the company
   -  Stock manager  
      This is the user role that manages the inventory of the whole center.
   - Security Officer  
      This user role handles the initial vehicle admitting when a  vehicle is brought to the center for a service or repair and security clearance when the vehicle leaves the premises
   - Foreman  
      This user role supervises service technicians
      (Also in our research, we found out that a foreman also does the recruitment and employment management for technicians) and makes sure services are up to standard by overseeing the whole repairing/servicing process from start to finish. Also in the service/repair scenario, the foreman takes vehicles for a test drive and creates fault reports as well.
    - Technician  
       These roles are the ones who do the servicing/repairing. They also connect with the foreman during the initial inspection of the vehicle and create a status report. Also, they need to update progress on repairs as well. These roles are supervised by the foreman role
    - Customer Care staff  
     Aside from answering phone calls and directing them to the relevant section, they also engage in chats from the customer website's chat now for help feature.
    - Administrator  
    This is the main management role of the service center.
    This role has control over all of the system and is the user role that manages all of the employees
    - Billing staff  
        This user role generates invoices and quotations based on service estimations created by foreman/technicians and for product purchases like spare parts and other automobile accessories

And we've identified the following features for these user roles

1.  Customer
    - All customers(regardless of whether they have an account), can search for products and services on the company's customer-facing website customers who have an account can add spare parts/accessories to a cart and checkout as well
    - customers(authenticated) can make appointments for any service category they desire through the website
    - customers can live chat with support staff 
    - customers who have an account can visit their profile and do the following things
        - see their pending orders
        - see past service records
        - after booking an appointment, customers receive appointment details and a QR code and they can use it to admit the vehicle to the center on the appointment day.
        - see their upcoming appointments
        - receive reminders when an appointment date is closing in
        - see their vehicle status
        - add reminders for servicing 
        - progress of repairs
        - customers will receive scheduled reminders and suggestions to service from the company via emails and SMS.

2. Stock manager

   Manages all the product stock of the company
   including spare parts, accessories etc. We identified the following features stock managers can add new products
   - Stock manager can update details about products
   - Can enter new stock for a product after buying from a supplier
   - Add/ Update / Delete suppliers
   - Generate various reports to analyze the sales performance of products
   - When an online order comes through the website, process it.
   - properly distribute parts required for on-premises servicing/repairs

3. Security Officer

   Security officer manages admittance and clearance of vehicles
   We've identified the following features for this use case
    - Scan the QR code received by customers who made an appointment to make sure that they are legit appointments
    - After doing an initial inspection, creates a report with
    outside appearance and any defects to make sure customer won't file false complaints about wrongdoing by the company.
    - After getting info about issues he's facing from the customer, creates a report and sends it to the foreman.
    - After a servicing, checks the bill/invoice and also check if something is wrong based on the initial inspection done during admitting




