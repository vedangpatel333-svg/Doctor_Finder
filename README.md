# Doctor Finder

Doctor Finder is a web application for booking doctor appointments online. Patients can search for doctors by name, location, or speciality, book appointments, and pay online, instead of having to call or visit a clinic in person. The system has three types of users: patients, doctors, and an admin.

I built this as my final year project for my B.Sc. in Information Technology at Ganpat University. It was my first full-stack project, and I used it to learn how a Java web application fits together from the database up to the front end.

## What it does

Patients can register, log in, and reset their password by email. They can search for doctors, book or cancel appointments, pay through PayPal, and leave feedback after a visit.

Doctors can manage their profile, view their upcoming appointments, and read the feedback patients leave for them.

The admin manages the whole system: adding or removing doctors, managing patient and doctor records, and overseeing appointments, feedback, and payments from a dashboard.

## Built with

- Java (Servlets, MVC pattern) and JSP for the back end
- MySQL for the database, accessed through JDBC
- HTML, CSS, Bootstrap, JavaScript, and jQuery for the front end
- Apache Tomcat 9.0 as the server
- Developed in Eclipse

## Running it locally

1. Clone the repository and import the project into Eclipse.
2. Create a MySQL database named `doctor_finder` and set up the required tables.
3. Update the database connection details in `src/com/DBconnection/DBconnection.java` to match your local setup.
4. Deploy the project to Apache Tomcat 9.0.
5. Open `http://localhost:8081/Doctor_Finder/home.jsp` in your browser.

## Notes

This is a learning project, so there are a few things I would do differently now, such as hashing passwords instead of storing them as plain text and moving the database credentials out of the source code into a config file. I have kept the original structure largely intact as a record of where I started.

## Author

Vedang Patel, B.Sc. Information Technology, Ganpat University (2020)
