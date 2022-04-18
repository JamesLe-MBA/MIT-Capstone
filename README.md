# James Le Global Credit Union (GCU)

MIT Capstone: Full-Stack Banking Application

Website Deployment: AWS S3 Bucket

# <div align="center">GCU = Crypto Currency + Blockchain</div>


### <div align="center">Description</div>

This MIT capstone is a 3-tier architect for frontend, backend, and database.
Full-stack MERN (MongoDB, Express, React, & NodeJS) uses JavaScript, JSON, React, Formik, API & more. 

### <div align="center">Instructions</div>
 1. Click on this link for live view, https://jamesle-blockchain.s3.amazonaws.com/index.html#/

 
### <div align="center">License Information</div>
 - [MIT License](https://mit-license.org/)


### General Features:

- [x] Create an account with an email address and password
- [x] Account log in with correct email and password
- [x] Transactional widthraw or deposit with updated balance in real time
- [x] Information persists across logins for database
- [x] Statement of transactions
- [x] After successful deposit or withdraw, "amount" field becomes empty for new entry
- [x] Negative balance not permissible

### Login validations:
- [x] before any operation, user `MUST be logged` (with Create Account or Login)
- [x] creating an account fires an `automatic login`
- [x] added a `log off` button with conditional when user is already logged in
- [x] when not logged in, operation Cards will show `Please log in` instead of regular content (Deposit, Withdraw, Statement)
- [x] when user is logged in, the `Create Account` and `Login` will show the `Logoff` button only

### Data validations:
- [x] Alerting notification when negative values submitted 
- [x] Alerting notification when empty field submitted
- [x] Alerting notificaiton when password length < 8 charaters
- [x] Alerting notificaiton when submitted email format not real 


## Roadmap of future improvements
•	Roles for different users, such as a bank employee vs customer (authorization)
•	Money transfer between users
•	Account types, such as checking vs savings accounts
•	Assignment of random account numbers to new accounts
•	User profile updates that are persistent
•	Check deposit by taking a picture of the check
 
 

## James Le Global Credit Union
![Image of James GCU](GCU.jpg)
