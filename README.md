
# UnSAFE Bank
Welcome to UnSAFE Bank - Vulnerable Banking Suite

## About
UnSAFE Bank is a core virtual banking suite designed with the aim to incorporate the cybersecurity risks and various test cases such that newbie, developers, and security analysts can learn, hack and improvise their vulnerability assessment and penetration testing skills on Web, Android and iOS application.

## Application Features
It currently consists of the following functionalities:
 * Funds Transfer
 * View Account Statement
 * Add/View Beneficiary

Note: New features and vulnerability integration is under development.

## Vulnerability Coverage
Say it intentionally or unintentionally, we have introduced vulnerabilities which varies from low severity to critical severity. 

## Setting up the environment

### Dependencies
1. [git](https://www.atlassian.com/git/tutorials/install-git).
2. [docker-compose](https://docs.docker.com/compose/install/).
3. Make sure that port 80 of your laptop/desktop does not have a running service.
4. Android/iOS device for mobile application testing.

### Setting up the server
1. Clone the repository on your system
`git clone https://github.com/lucideus-repo/UnSAFE_Bank.git`
2. Navigate to the UnSAFE-Bank/Backend directory
`cd UnSAFE_Bank/Backend`
3. Start docker service (if not running) 
`sudo service docker start`
3. Start the containers
`docker-compose up -d`

### Installing iOS Application
1. Download and install the Cydia Impactor on your system.
2. Connect your iPhone to the system and open Cydia Impactor.
3. Drag and drop the **UnSAFE Bank.ipa** file placed in the **iOS Application** directory.
4. Trust the developer profile (if required).

### Test Connectivity Status
1. Connect your iPhone and System to the same internet connection.
2. Check you system IP address (ifconfig) and the port on which backend is running (Default port is 80).
3. Open the iOS Application and provide the connection strings on the top right corner to connect.
4. You are successfully connected if there is no error message on your iPhone

### Login Credentials
Customer ID and password is required to login into the application. You can always sign up as a new user in the application. 

On successful sign up:
1. You will be provided with your Customer ID corresponding to your account. Always note your Customer ID and keep it SAFE for further usage.
2. Your dummy PII and account information would be created automatically.
3. Default beneficiaries would be added in your account.
4. Virtual money would be added in your account ranging from 1 to 5 lakh.

### Existing User Bank Accounts
Following data can be used to perform actions such as add beneficiary, funds transfer etc.
| Account Holder | Account Number | IFSC Code |
| -------------- | -------------- | ----------|
| Rubal Jain | 149812733485 | IFSC00002 |  
| Sahil Pahwa | 261562410205 | IFSC00008 |
| Chetan Kumar | 618850572087 | IFSC00009 |
| Vibhav Dudeja | 263021552894 | IFSC00010 |
**********

### Encountered a bug or want to suggest something?
If you come across any functional bug in the application or want to suggest the improvements, kindly report the same. We will look into it at the earliest. :)

### License
Open Source
