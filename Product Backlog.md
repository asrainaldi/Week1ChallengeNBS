Link to Dev ops stories
https://dev.azure.com/asrainaldi/TDP%20-%20Week%201/_workitems


**EPIC:** A online system allow users to come to the cinema.
<br />
*Feature:* Allow users to see fucture viewings and create an account
- As a user when visiting the cinema web site I would like to see the timings of the films
- As a user when visiting the cinema I would like to create an account so i can make future bookings
  - **Given** a new user visits the site **When** registration **Then** a new user is created

- As a user when logged into the site I would like to see my previous bookings so i can check my order
  - **Given** a signed in user **When** searching for previous bookings **Then** the list of all previous bookings is shown

*Feature:* Allow users to book a seat at for a future viewing
- As a user when logged in I would like to choose a film to watch so i can start a booking
- As a user when logged in with a film selected I would like to select a time to see the film
- As a user when logged in I would like to see the available seats for the film time i have selected so that i can select my seats
- As a user I would like to pay for my selected seats so i can create my reservation
- As a user when I have created my reservation I would like to receive a confirmation email so i can be assured i have ordered correctly
  - **Given** a valid booking **When** payment has completed **Then** a email is sent to the user

**EPIC:** A method to adminastrate the site
<br/>
*feature:* Allow 3rd party advertisment to the site
- As an admin I would like to apply a 3rd party advert into the home page so i can show trailers
- As an admin I would like the adverts to be able to be controlled by a 3rd part advertisement provider

*feature:* admin area content magaement
- As a Admin I would like an manage the content of the site through an administration portal
- As a Admin I would like to administrate the staff members that can use the site so i can update current staff members
<br/>

**EPIC:** Allow staff members to manage bookings 
<br />
*feature:* Allow Staff member to manage user bookings
- As a staff member i would like to be able to edit user bookins by a given order ID so i can change their booking
- As a staff member i would like to be able to search for a user booking by name so i can find a booking
<br/>

Total effort of 76 story points. If we assume 5 point per day per developer = 3 weeks of just development time. Will need to acount for planning, testing, deploying and feedback.

Priority is describred by using the MoSCoW per release sechedule
- Must have
- Should have
- Could have
- Will not have
