Cupid_Meet_App-.NET-Angular-Project-002

# Cupid_Meet_App

## Introduction

Cupid_Meet_App is application for meeting people

## Features

- Real Time Chat - SignalR
- Multiple Photos Upload
- Roles
- .NET REST API
- TypeScript
- Cloudinary - for image storage

## How to use?

- 0.Download the repository, extract it to folder and open with Visual Studio Code

Open Terminal in "API" folder:
2.Add appsetting.json with:
`{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "TokenKey": "super secret unguessable keys super secret unguessable keys super secret unguessable keys",
  "CloudinarySettings": {
    "CloudName": "YourCloudName",
    "ApiKey": "YourApiKey",
    "ApiSecret": "YourApiSecret"
  },
  "AllowedHosts": "*"
}`

3.Open "MeetApp.sln" with visual studio code
4.dotnet run

Open Terminal in "client" folder:
1.npm install
2.ng serve
3.Start on: https://localhost:4200/

## Photos

All Matches With-Sorting,Pagination,OnlineStatus:

![image](/API/wwwroot/assets/Images/1All_Matches_With-Sorting,Pagination,OnlineStatus.png)

Buttons For Chat Like And Profile:

![image](/API/wwwroot/assets/Images/2Buttons_For_Chat_Like_And_Profile.png)

Real Time Chat:

![image](/API/wwwroot/assets/Images/3Real%20Time%20Chat.png)

Upload Multiple Photos:

![image](/API/wwwroot/assets/Images/4Upload%20Multiple%20Photos.png)

Edit Photos:

![image](/API/wwwroot/assets/Images/5Edit%20Photos.png)

User Photos:

![image](/API/wwwroot/assets/Images/6All_User_Photos.png)

Nottifications::

![image](/API/wwwroot/assets/Images/7Notifications.png)

Profile Page:

![image](/API/wwwroot/assets/Images/8Profile%20page.png)

Admin Panel - User Management:

![image](/API/wwwroot/assets/Images/9Admin_Panel-User_Management.png)

Edit User Role:

![image](/API/wwwroot/assets/Images/10Edit_User_Role.png)

Admin Panel - Confirm Or Reject Photos:

![image](/API/wwwroot/assets/Images/11Admin_Panel-Confirm_Or_Reject_Photos.png)

Edit Profile:

![image](/API/wwwroot/assets/Images/12Edit%20Profile.png)

Members i like (2):

![image](/API/wwwroot/assets/Images/13Members%20i%20like%20(2).png)

Members i like:

![image](/API/wwwroot/assets/Images/13Members%20I%20like.png)

Members who like me:

![image](/API/wwwroot/assets/Images/14members%20who%20like%20u.png)

Mutual Matches:

![image](/API/wwwroot/assets/Images/15Mutual%20Matches.png)

Unread Messages:

![image](/API/wwwroot/assets/Images/16unread%20Messages.png)

InboxMessages:

![image](/API/wwwroot/assets/Images/17InboxMessages.png)

Outbox - Sent Messages:

![image](/API/wwwroot/assets/Images/18Outbox%20-%20Sent%20Messages.png)

Landing Page:

![image](/API/wwwroot/assets/Images/19LandingPage.png)

Register/Login:

![image](/API/wwwroot/assets/Images/20RegisterLogin.png)





