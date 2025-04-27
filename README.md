𝐁𝐚𝐫𝐛𝐞𝐫 𝐑𝐞𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧 𝐒𝐲𝐬𝐭𝐞𝐦 

This is a full-stack web application built to handle appointment bookings for a barber shop. Customers can easily view available barbers and time slots on a selected day and book an appointment accordingly.

𝐓𝐡𝐞 𝐩𝐫𝐨𝐣𝐞𝐜𝐭 𝐢𝐬 𝐝𝐞𝐯𝐞𝐥𝐨𝐩𝐞𝐝 𝐮𝐬𝐢𝐧𝐠:

Backend: Java + Spring Boot (REST APIs)

Frontend: React.js

Database: MySQL

It focuses on providing a seamless and efficient reservation experience for both customers and barbers.

𝐊𝐞𝐲 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬 🚀

Customer Registration & Login: Secure signup/login for customers.

Barber Management: Barbers can have customized available times per day.

𝐀𝐩𝐩𝐨𝐢𝐧𝐭𝐦𝐞𝐧𝐭 𝐁𝐨𝐨𝐤𝐢𝐧𝐠:

Customers select a date.

See available barbers and their free slots.

Book a reservation in real-time.

Admin Panel : Manage barbers, appointments, and customers.

Booking Status Update: Customers can cancel or reschedule appointments.

Conflict Management: Prevents double-booking of the same time slot.

Real-Time Availability: Instant update of free slots after each booking.

𝐓𝐞𝐜𝐡 𝐒𝐭𝐚𝐜𝐤 ⚙️
Backend: Java, Spring Boot (MVC Architecture, RESTful APIs)

Frontend: React.js

Database: MySQL (JPA/Hibernate)

Other Tools: Postman (API Testing), Maven (Build Tool)

𝐃𝐚𝐭𝐚𝐛𝐚𝐬𝐞 𝐒𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞 📊
Customers Table: Stores customer information.

Barbers Table: Stores barber profiles and availability slots.

Appointments Table: Stores details of each booking (customer, barber, date, time).

𝐇𝐨𝐰 𝐈𝐭 𝐖𝐨𝐫𝐤𝐬 🔥
Customer signs up/logs in.

Selects a preferred date.

Views all barbers available along with free time slots.

Books an appointment by choosing a time slot.

Backend validates slot availability.

Appointment is saved and confirmation is shown to the customer.

𝐂𝐡𝐚𝐥𝐥𝐞𝐧𝐠𝐞𝐬 𝐒𝐨𝐥𝐯𝐞𝐝 🧠
Dynamic time-slot generation based on barber availability.

Managing concurrency (handling two customers trying to book the same slot).

Clean separation between backend logic and frontend UI.

Secure API endpoints and authentication flow.

Scalability: Easily extendable for multiple shops/branches.

𝐅𝐮𝐭𝐮𝐫𝐞 𝐄𝐧𝐡𝐚𝐧𝐜𝐞𝐦𝐞𝐧𝐭𝐬 🔮
Notification system (email/SMS) for booking confirmations.

Payment gateway integration.

Customer reviews and rating system for barbers.

Mobile App version.

𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧 𝐒𝐭𝐞𝐩𝐬 🛠️
Backend:

Clone the repo.

Run mvn clean install.

Setup MySQL database and update application.properties.

Run the Spring Boot application.

Frontend:

Navigate to frontend folder.

Run npm install.

Start frontend server using npm start.

# Visual representation

![schema](https://github.com/ramezcode1/salonBookingSystem/assets/135148978/41b56a90-8bc9-4d1d-b9f6-9c95729feedc)
