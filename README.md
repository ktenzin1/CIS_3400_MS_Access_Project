# CIS_3400_MS_Access_Project
This is a Microsoft Access application for a fictional veterinary clinic Yuki Clinic

Yuki Veterinary Clinic is a small clinic with 30 employees and 30 veterinarians. There are 30 pet owners who are registered with the clinic to receive services for their pets. This application developed in Microsoft Access serves a database management system for the clinic, enabling the CRUD (Create, Read, Update, and Delete) functions. 

Tables

It has tables used to store important information about the employees, veterinarians, pets, pet owners, appointments and services provided by the clinic. Each table has a unique ID used as the primary key for indexing and easy search for records. 

The relationship between pet owners and pets is one to many. One pet owner can own one or many pet owners. However, one pet can only be owned by one pet owner. Similarly, one employee and one veterinarian can provide services to one or many different appointments but one appointment can only be taken care of one employee and one veterinarian, for the purpose of this application. 

The use of foreign keys establishes dependency relationships between records and different tables. Example, the appointment ID in the appointments table becomes the foreign key in the services table to allow each record in the services table to be associated with a specific appointment in the appointments table. This relationship enables efficient data retrieval and management, allowing querying and analyzing services based on the appointments they are associated with. Additionally, it helps maintain data integrity, ensuring that services are properly linked to the corresponding appointments. 

The tables in the project are all in the third normal form. There are no duplicate records, every column in a table has atomic value, and there are primary keys for each table. This makes the table in first normal form. There is no partial dependencies which means that each non-primary key is entirely dependent on the primary key. This makes the table in the second normal form. Finally, there is no transitive dependency meaning that a non-key does not depend on any other non-keys in the table. This makes the table in its third normal form. 

Forms

Each table has an associated form that can be used by an employee to get necessary information about the pet, pet owners, to make an appointment with the clinic, document services (treatments) provided by the clinic, and create a bill for the pet owner to pay for the services received.

Data entered in each form is updated automatically in the tables making it a convenient data management tool. The forms have navigation buttons to create a user friendly system environment.  

Reports

Two sample reports have been generated from queries using tables. For example, the Yuki Services Report shows different treatments provided for different reasons for visit to the clinic along with the amount of billable amount for each service provided. Reports are used for analytical purposes and can be utilized by the clinic to understand their business operations better, target bottlenecks to solve issues, and improve performance. 


