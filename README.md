# Microsoft 365 Lab MS-900

I set up my own Microsoft 365 tenant and I am learning how to manage it hands on. This is lab practice to get ready for a helpdesk role. It is not work for a company.

Tenant AlmaraatLLC.onmicrosoft.com
Admin user SeklanAzeem@AlmaraatLLC.onmicrosoft.com
License shown in the admin center Office 365 E5 Non Profit Pricing
Where the work happens Microsoft 365 admin center

## What I did

### Module 1 Admin center and users
I opened admin.microsoft.com as admin. This is the control panel. I manage users here.
I added a user. I gave the user a name and a login.
I picked Assign user a product license. I ticked Office 365 E5 Non Profit Pricing. A license is permission to use the apps. Without it the user cannot open Outlook or Teams or Word.
I checked Active users again. I saw the new user with the license.
I practiced password resets. A password reset lets a user sign in again when they forget their password.
I checked Outlook and OneDrive and Viva Engage and Stream and SharePoint and Lists as the test user. This shows the license works and the apps open.

### Module 2 Teams
I logged in as Test User. I opened Teams. I made a team. I made a messaging policy to turn off Giphy in conversations and turn off Delete sent messages. A messaging policy is a rule about chatting. A company might turn GIFs off to keep it professional. I went back and checked the GIF button is gone.

### Module 3 Groups and apps
I made a Microsoft 365 Group. I explored Planner and Forms and Power BI. I looked at Intune. A group lets people share files and apps. Planner is for tasks. Forms is for surveys. Power BI is for reports.

### Module 4 Security and compliance
I built a Conditional Access policy that requires MFA. MFA is a second check when you sign in. Conditional Access is a rule that says when the second check is needed.
I turned off Security Defaults first. Security Defaults is the basic protection that Microsoft turns on. I turned it off so my own policy could control sign ins.
I tested the policy as Test User. I signed in and I saw the MFA check.
I looked at PIM. PIM gives admin rights just in time. A person gets admin access for a short time and then it goes away.
I checked Defender and Secure Score. Defender watches for bad files. Secure Score shows how safe the tenant is.
I checked Defender for Cloud Apps. I made a sensitivity label and I published it. A label marks files so people know how to handle them.
I checked Compliance Manager and Customer Lockbox. Compliance Manager tracks rules the company must follow. Customer Lockbox means Microsoft asks me first before they look at my data.

### Module 5 Licensing
I opened Billing and Licenses. I assigned licenses. I exported users. I unassigned licenses. I checked Requests. This shows I can give and take away licenses when people join or leave.

## Screenshots

Screenshots for each module are in the screenshots folder in this repository.

## Source

Lab steps are based on the CloudLabs-AI MS-900 lab at https://github.com/CloudLabs-AI/MS-900-Lab-Content

## Tools

Microsoft 365 admin center Microsoft Entra ID Microsoft Teams Windows 11
