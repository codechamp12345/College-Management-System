
# College Management System

The College Management System is a MERN Stack-based system with three different login portals for students, faculty, and admin.

## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express

**Database:** MongoDB


Youtube Link: https://www.youtube.com/watch?v=LY4UhPadZCs&ab_channel=KrishJotaniya


## Student Features

- Internal Marks: Access to view internal marks for courses
- External Marks: Access to view external marks for courses
- Course Materials: Ability to download course materials
- Notices: Access to view notices
- Timetables: Access to view their own timetables
- Password Update: Ability for students to update their passwords

## Faculty Features

- Student Details: Ability for faculty to view student details
- Password Update: Ability for faculty to update their own passwords
- Notices: Ability for faculty to add notices
- Materials Upload: Ability for faculty to upload course materials
- Timetable Management: Ability for faculty to manage timetables
- Exam Mark Recording: Ability for faculty to record internal and external exam marks

## Admin Features

- Account Creation: Ability for admins to add new students, faculty, and admin accounts
- Account Details Modification: Ability for admins to modify the details of each account
- Subject Management: Ability for admins to add/edit subjects
- Notices Management: Ability for admins to add/edit notices
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

First add the below given env data and run the frontend and backend then open Mongodb Compass and there you will see the name of your Collection open it and select Admin Details table and add this document (Change the name according to the data) 

```
{
  "employeeId": 123123,
  "firstName": "YOUR_DATA",
  "middleName": "YOUR_DATA",
  "lastName": "YOUR_DATA",
  "email": "test@admin.com",
  "phoneNumber": YOUR_DATA,
  "gender": "Male",
  "profile": "https://cdn.britannica.com/42/193142-050-F69B1A23/Sundar-Pichai-Google.jpg",
} 
```

Then add below document without any changes in Admin Credentials

```
{
  "loginid": 123123,
  "password": "112233",
}
```

Now login into admin with Above mentioned login and password. You can add student and faculty from admin.

Frontend Side:
`REACT_APP_API`
`REACT_APP_AUTHDOMAIN`
`REACT_APP_PROJECTID`
`REACT_APP_STORAGE_BUCKET`
`REACT_APP_SENDERID`
`REACT_APP_APPID`

Backend Side: 

`MONGODB_URI`

