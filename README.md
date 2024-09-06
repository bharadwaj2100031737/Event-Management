# Event-Management
Event management system using Spring boot and mivroservices 
The Event Management System consists of three primary modules: Admin, Manager, and Customer.

Customer Module:

Registration and Login: Customers can register and create their own login credentials.
Event Viewing and Booking: After logging in, customers can view all available events, book events of their choice, and view/manage their booked events.
Profile Management: Customers can manage their profile information, such as updating their personal details or changing their password.
Manager Module:

Registration and Approval: Managers can register, but their access is restricted until approved by an admin.
Event Management: Once approved, managers can log in to:
Post new events.
View all events they have posted.
Monitor bookings for their events, including details about the customers who have booked.
Send emails or updates to customers about event changes, reminders, or announcements.
Admin Module:

User Management: Admins have complete control over the customer and manager details. They can:
Approve or deny manager registrations.
Block or remove access to any manager or customer.
Event Oversight: Admins can view all events posted by managers and access detailed statistics, such as total events, total bookings, customer lists, etc.
Advanced Features: Includes various functionalities like:
Validations for every login, registration, and other actions to ensure data integrity.
Category-wise event alignment and filtering for better organization.
Pagination for efficient data display.
Additional Features:

User Interface (UI) and Experience (UX): The system will have advanced UI designs with 3D elements and realistic photos to enhance the visual experience.
Backend and Database: The backend will be developed using MySQL for data management and storage.
