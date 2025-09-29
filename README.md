# Bankingonboardingmodule

Banking-Onboarding-moduleAdd commentMore actions
This is a backend-only Spring Boot application developed for Banking Customer Onboarding. It supports onboarding workflows including user registration, email verification, SMS OTP verification using 2Factor API, Razorpay payment integration, and document/image upload handling. [11:50 am, 6/6/2025] Tech Stack

Backend: Spring Boot, Spring Data JPA, REST API
Database: MySQL
Payment Gateway: Razorpay
SMS Gateway: Twillo API
Email Service: Gmail SMTP
ORM: Hibernate
Build Tool: Maven
✨ Features
✅ Customer onboarding form via REST API
✅ Email Verification using tokenized link
✅ SMS OTP Verification via 2Factor API
✅ Razorpay payment gateway integration for onboarding charges
✅ *… [11:50 am, 6/6/2025] Akhil: src/ ├── main/ │ ├── java/ │ │ └── com.banking/ │ │ ├── controller/ │ │ ├── service/ │ │ ├── model/ │ │ ├── repository/ │ │ └── utils/ │ └── resources/ │ ├── application.properties │ └── static/ or templates/ (if needed) └── testThank you for your business! We look forward to working with you again. [11:50 am, 6/6/2025] Akhil: ---
🛠️ Configuration
🔐 application.properties
# Database
spring.datasource.url=jdbc:mysql://localhost:3306/banking_db
spring.datasource.username=root
spring.datasource.password=yourpassword

# JPA
spring.jpa.hibernate.ddl-auto=update

# Email (Gmail SMTP)
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=youremail@gmail.com
spring.mail.password=yourapppassword
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true

 

# Razorpay
razorpay.key.id=YOUR_RAZORPAY_KEY_ID
razorpay.key.secret=YOUR_RAZORPAY_KEY_SECRET
