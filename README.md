# APITesting

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

## Newman and Report Installation Process:

Newman Install Command:

```bash
  npm install -g newman-reporter-htmlextra
```
  Newman Html Report Install Command:
```bash
  npm install -g newman-reporter-htmlextra
```
## Test case list:
1. Create Booking : Create a new booking in the API
2. Get Booking : Return a specific booking based upon the booking id provided
3. Update Booking : Update a current booking
4. Delete Booking : Delete a created booking
   
## Newman Report Summary:
