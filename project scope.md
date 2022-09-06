# Project Scope
## Project Identification and Boundaries

In the project, we hope to build an automobile service center & Part shop management system for a hypothetical automobile services company.

- Proposed system has 7 user roles. Those are,
    1. Customer (both authenticated and not)
    2. Stock Manager
    3. Security Officer
    4. Office Staff Member
    5. Foreman
    6. Technician
    7. Admin

- Through this project, we hope to connect this vehicle service center with its customers. Also, the inner process of the service center will be digitized using this system. Customers will be able to order products online, make appointments online, and manage service/repair of their vehicles and from the company's side, they will be able to manage the service/repair process, stock management and employee management. This system hopes to increase the efficiency of the service station and user satisfaction.


## In-scope

Below are the features a customer (vehicle owner) can expect from the system.

- Any customer can visit the website and discover what are the service and products offered by the company.
- Customers with accounts will be able to add products to a cart and checkout them to deliver to their location.
- Customers with accounts will be able to select service types and make an appointment online by seeing available timeslots.
- Customers with accounts will be able to see pending orders, ongoing service progress, past service history etc.

Stock manager role can expect these features.

- Manage info about suppliers.
- Manage spare parts/accessory inventory.
- Handle online orders.
- Distribute products for in-house services/repairs.

Foreman role gets these features.
- Generate fault reports.
- Assign technicians to tasks and update service job cards.
- Oversee the progress of vehicle repairs & services.

In the perspective of Security officers, they get the following features.
- validate appointment dates.
- generate admitting reports and check them when leaving.

Technicians will be able to do following things using the system.
- get notified when they are assigned to a job.
- Mark tasks as complete in the job card.
- view previous jobs they were assigned to.

Office Staff Members will have the following features in the system

- Open job cards for customers, create accounts for them and create new vehicle entries in the system.
- Manage invoicing customers.
- Make appointments on behalf of customers.

Admin gets access to following features (doesn't mention all the features as they are distributed appropriately with other user roles )

- Manage employee accounts.
- Analytics.

System will use notifications in some features like,

- when notifying assignment to a job to a technician.
- Notify customer after job finishes
- Notify foremen when all tasks are done by the technicians

Also payment handling will be implemented  as well for the online ordering website

## Out-scope

Although our system takes care of many things in the service station, some aspects are out of the scope of our project.

- Cash register and physical payment handling

    Since this is a web-based system and it's not straightforward to connect cash registers(physical payments) for the office staff members when accepting payments from customers, our system doesn't handle that. Instead, office staff members will have to manually mark invoices as paid.

- Employee salary management & attendance tracking

    Our system doesn't handle the aspect of employee salary management 
    and it doesn't provide features to track the attendance of employees

- Delivery progress management,

    Although the system notifies customers when orders are processed and sent to deliver, the proposed system doesn't include features to track its location  and status
- Direct integration with printers

    Printing invoices/quotations and other reports are only done through the web browser interface for printing, our system doesn't directly connect with any specific printers.

