# Senior Center App Scope Doc
#### Trent Baker, Ben Bushnell, Brian Foley, Ian Hecker, Grace Walkuski
#### Montana State University, ESOF 423, Spring 2019

## Summary
This document outlines the specifications of the Senior Center App Project for the Belgrade Senior Center.

## Objective

### Business Need
The Belgrade Senior Center wants to be able to electronically record, store and reference client data in their center. They need to be able to view and manage all their clients via a web app. It would allow the clients to be sorted and contacted based on characteristics or events they have attended. There would also be a view that allows clients to sign into events. 

Track event attendance for:
- Blood Pressure Checks (Every other Thursday)
- Tax services (Tuesdays during tax season)

### Proposed Solution
...

## Product Description

### Desired Functionality
- Data Stored about Clients: (MVP)
  - Name
  - Address
  - Birthday -> Age
  - Phone number
  - Email address
  - Emergency contacts (name, address, phone number, relationship)+
  - Medical information (diets, allergies, disabilities, medications, medical issues)
  - Membership status (start date, renewal data, date paid, payment method (cash/check & check #))
  - Meals (home delivered vs. in center, combination?)
  - Activities of interest 
    - Payment (date paid, payment method (cash/check & check #), payment recurrence daily/weekly/monthly/yearly)
  - Social events attended and Services used (blood pressure checks, tax services, driving courses, educational classes)
    - Can be open to non-members (still should sign in or have some way of taking attendance)
  - Number of duplicated and unduplicated members for each activity and service
  - Notes section for other more unpredictable information?
  - Waivers signed
  - Forms filled out (expiration date)
- Be able to print reports for grant writing (MVP)
  - Area 4 form (need: budget, number of people served, number of meals served, profit)
  - Mast Form (filled out when applying for membership, info goes to both places)
  - Gallatin United Way
  - Meals on Wheels (extention of Mast form, same form for in center and in home meals) (non mebers can eat but they need to have a mast form filled out)
- Easily add new services and activities (MVP)
  - Schedule events and classes
  - Schedule recurring events (reach goal)
- Administrators have full access to edit all data (MVP)
- Volunteers have more limited data access (MVP but maybe lower priority)
  - Can sign in and make edits to certain information
  - History of hours worked
  - Record data changed while "on duty"? (reach goal)
  - Process volunteer applications (is it an application or a sign up?)
- Members can sign into events (MVP)
  - Register in advance (reach goal)
- Medical Closet Inventory (reach goal)
- Newsletter with Calendar and Menu (reach goal)

### Specifications and Technologies
#### Profiles/Views
We are planning to create three different types of profiles and views available in the app
Login as:
- Admin
  - username and password to login
  - Has full rights to view and edit all the information stored in the database
- Volunteer
  - username and password to login
  - has limited rights to view and edit the information stored
  - can add new members
  - cannot see sensitive medical information
- Senior (different term?)
  - use first/last name to sign in
  - can sign themselves into events
  - recieves notifications about missing payment/information                        

## Belgrade Senior Center Visits
### Initial Visit 1-24-19
#### Summary/Notes
...
#### Questions
1. Who is maintaining client profiles? 
   - Admins have full rights to edit all the information
   - Volunteers have more limited access (not medical information, but they can add a new member)
2. Are there different membership levels?
   - No, just $15/month (year?)
3. Are there any clients who take both home delivered and in center meals?
4. Should we be able to store medical information like from the blood pressure checks?
   - No, but we should collect how many people use the blood pressure services
   - When they sign into an event on the same day that there is a blood pressure check, ask them if they are going to use the blood pressure services
   - Also have the same pop up if they need to pay their membership fee or are missing any other information or forms
5. What's the difference between the activities of interest and the services used (yoga classes and educational classes seem like they should be in the same category)?
6. What are duplicated and unduplicated members?
7. For managing volunteers, are the seniors doing the volunteering or are other community members volunteering at the senior center?
8. Should members be able to register in advance for classes? Or just sign in when they get there?
9.  Information (eventually) needed:
	- lists of classes/activities offered
	- example reports for grants
	


