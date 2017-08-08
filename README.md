# K.I.D.S. - Kollective Impact Data Service
## Indy Civic Hack 2017 Project

A web app to create a feedback loop between a third party interacting with a foster child and the department of child services for the state of Indiana.

#### Team Name: Civic Team 6
#### Team Members: 
* Kyle Peeler
* Trent Spice
* Josh Martin
* Jake White
* Brian Herhusky

Challenge: Department of Child Services [(see DCS-Challenge.pdf)](http://indychamber.com/index.php/download_file/2767/1559/)

Technologies Used:
* [PactSafe React SDK](https://github.com/pactsafe/pactsafe-react-sdk)
* React.js Front-end
* Firebase or MS SQL Server Back-end
* FAAS Back-End (Docker, Node.js, Python, Prometheus) https://github.com/alexellis/faas/blob/master/TestDrive.md


App is split into four parts:

* kids-receiver-client is the dashboard view for the Department of Child Services
* kids-sender-client is the client to be used by a third party to submit information to Department of Child Services
* FAAS services, Data obviscation and encrytion for privately linking matching PII. 
* PactSafe - Notary service to automate MOU, EULA for third party NGOs.

To start either app, enter the directory and run `yarn start`
