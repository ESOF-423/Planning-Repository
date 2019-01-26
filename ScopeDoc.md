# Senior Center App Scope Doc

Trent Baker, Ben Bushnell, Brian Foley, Ian Hecker, Grace Walkuski

Montana State University, ESOF 423, Spring 2019

## Summary

This document outlines the specifications of the Senior Center App Project for the Belgrade Senior Center.

## Objective

### Business Needs

The Belgrade Senior Center wants to be able to electronically record, store and reference client data in their center. They need to be able to view and manage all their clients via a web app. It would allow the clients to be sorted and contacted based on characteristics or events they have attended. There would also be a view that allows clients to sign into events.

Track event attendance for:

- Yoga
- Exercise
- etc.

Track Service attendance for:

- Blood Pressure Checks (Every other Thursday)
- Tax services (Tuesdays during tax season)

### Proposed Solution

...

## Product Description

## Desired Functionalities

1. Data Stored about Clients: (MVP)

   Required Info

   - Name
   - Address
   - Birthday
   - Age
   - Emergency contacts (name, address, phone number, relationship, etc.)
   - Membership status
     - Default to unpaid, optional to upgrade to paid

   Optional Info

   - Email address
   - Phone number
   - Upgraded Membership status (start date, renewal data, date paid, payment method (cash/check & check #))   - Payment (date paid, payment recurrence daily/weekly/monthly/yearly)
     - Can be open to non-members (still should sign in or have some way of taking attendance)
   - Meals (home delivered vs. in center, combination?)
   - Activities of interest
   - Social events attended and Services used
     - blood pressure checks, tax services, driving courses, educational classes
   - Notes section for other more unpredictable information?
   - Waivers signed
   - Forms filled out (expiration date)
   - Days visited
   - times/duration of visits
   - food allergies, need to know medical info

   Sensitive Info

   - Medical information (diets, allergies, disabilities, medications, medical issues)
   - Income level (For poverty level for other forms)
   - payment method (cash/check & check number)
   - Tax Service Info

2. Data Stored about Volunteers (MVP)

   Required Info

   - Name
   - Birthdate
   - Work Signed Up For
     - Options of work to choose from
   - Emergency Contact
   - Hours worked
     - Check in/out times?

   Optional Info

   - etc.

3. Manage Forms

   - Be able to print reports for grant writing (MVP)
   - input information into forms online
   - auto populate forms information
   - store filed forms online

   Focus Forms:

   - Area 4 form

     - need: budget, number of people served, number of meals served, profit
     - Automated population of form for grant writing

   - Mast form

     - filled out when applying for membership, info goes to both places

   - Gallatin United Way form

   - Meals on Wheels form

     - extension of Mast form, same form for in center and in home meals) (non members can eat but they need to have a mast form filled out

4. Admin, Volunteer, Member Privileges

   Administrator Privileges

   - Easily add new services and activities (MVP)
   - Administrators have full access to edit all data (MVP)
   - Access Medical Closet Inventory (reach goal)
   - Send Newsletter with Calendar and Menu (reach goal)
   - Search and Sort members, events, services, etc. (MVP)
   - Edit volunteer hours
   - Check in/out medical closet items

   Volunteer Privileges

   - Volunteers have more limited data access (MVP but maybe lower priority)
     - Need to see member's ages for age benefits
     - ex. over 60 eat free
   - Can sign in and make edits to certain information
   - History of hours worked
   - Record data changed while "on duty"? (reach goal)
   - Process volunteer applications (is it an application or a sign up?)
   - Receive Newsletter with calendar and menu
   - Fill out forms to register new members
   - Check in/out medical closet items

   Member Privileges

   - Members can sign into events (MVP)
   - Register in advance (reach goal)
   - Input basic information

## Specifications and Technologies

`TODO`

## Belgrade Senior Center Visits

Initial Visit 1-24-19

Summary/Notes

`TODO`

Questions

1. Who is maintaining client profiles?
   - Admins have full rights to edit all the information
   - Volunteers have more limited access (not medical information, but they can add a new member)
2. Are there different membership levels?
   - No, just $15/month (year?)
3. Are there any clients who take both home delivered and in center meals?
   - Not permanently. If a member is injured or becomes sick, they may take home-delivered meals temporarily, but no member will have home delivery and in center meals concurrently
4. Should we be able to store medical information like from the blood pressure checks?
   - No, but we should collect how many people use the blood pressure services
   - When they sign into an event on the same day that there is a blood pressure check, ask them if they are going to use the blood pressure services
   - Also have the same pop up if they need to pay their membership fee or are missing any other information or forms
5. What's the difference between the activities of interest and the services used (yoga classes and educational classes seem like they should be in the same category)?
   - Social events - things like card games that are likely irrelevant to grants
   - Exercise - fitness and motion activities that need to be tracked for grant purposes
   - Services - things like tax prep sessions that are often open to the public
6. What are duplicated and unduplicated members?
   - duplicated is like page views, total number of check-ins regardless of who checked-in
   - unduplicated is like unique visitors, each person only counts once even if they attend every event
7. For managing volunteers, are the seniors doing the volunteering or are other community members volunteering at the senior center?
   - Both seniors and younger community members, volunteer interface needs to be simple enough for the seniors
8. Should members be able to register in advance for classes? Or just sign in when they get there?
   - Primary focus should be on walk-ins. Many members do not have email or computers at home.
   - If we have a pre-register function, then we would need to check again at the door otherwise data would not be valid for grant writing (40 people RSVP, 4 show up, cannot claim 40 people attended)

Information (eventually) needed:

- lists of classes/activities offered
- example reports for grants