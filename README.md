# APITesting
This repository contains API tests for Restful Booker demo website(https://restful-booker.herokuapp.com)- an API playground which allows to perform all CRUD methods. The tests were created and performed in Postman and then exported to JSON files.

## How to run this project

- Clone this project
- Open with Postman / Command Shell
- Run Command:

```bash
  newman run Booking.postman_collection.json -e Booking.postman_environment.json
```
- Run Command for Report:
```bash
  newman run  Booking.postman_collection.json -e Booking.postman_environment.json -r cli,htmlextra
```
## Tools
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## 🗃️ Newman and Report Installation Process

Newman Install Command:

```bash
  npm install -g newman-reporter-htmlextra
```
  Newman Html Report Install Command:
```bash
  npm install -g newman-reporter-htmlextra
```

## API Documentation
The documentation can be found at https://restful-booker.herokuapp.com/apidoc/index.html
## Test case list:
1. Create Booking : Create a new booking in the API
2. Get Booking : Return a specific booking based upon the booking id provided
3. Update Booking : Update a current booking
4. Delete Booking : Delete a created booking
   
## Newman Report Summary:
![report](https://github.com/AbidaAfrin/APITesting/assets/126371236/3370ca66-cdbd-45ab-9eae-366b21882b8d)
![report1](https://github.com/AbidaAfrin/APITesting/assets/126371236/08c7d9a7-5d07-445d-8e2f-cfd008cb3142)

