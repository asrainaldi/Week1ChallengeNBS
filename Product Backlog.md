Link to Dev ops stories
https://dev.azure.com/asrainaldi/TDP%20-%20Week%201/_workitems


**EPIC:** A online system allow users to come to the cinema. - 40 Effort
<br />
*Feature:* Allow users to see fucture viewings and create an account - 20 Effort
- As a user when visiting the cinema web site I would like to see the timings of the films - 5 Points
  - **Given** a hosted web site **When** a user visits the page **Then** the site should show the current film times
- As a user when visiting the cinema I would like to create an account so i can make future bookings - 5 Points
  - **Given** a new user visits the site **When** registration **Then** a new user is created
- As a user when logged into the site I would like to see my previous bookings so i can check my order - 5 Points
  - **Given** a signed in user **When** searching for previous bookings **Then** the list of all previous bookings is shown

*Feature:* Allow users to book a seat at for a future viewing - 20 Effort
- As a user when logged in I would like to choose a film to watch so i can start a booking - 8 Points
  - **Given** a set of available films **When** a film is selected **Then** a user is taken to the booking in page with film selected
- As a user when logged in with a film selected I would like to select a time to see the film - 3 Points
  - **Given** a future selected film **When** selecting a time **Then** a user is allowed to select a time for the viewing
- As a user when logged in I would like to see the available seats for the film time i have selected so that i can select my seats - 8 Points
  - **Given** a film and time **When** a user selects a seat/s **Then** the user is able to progress the booking
- As a user I would like to pay for my selected seats so i can create my reservation - 5 Points
  - **Given** a valid selection **When** a user progresses through to payment **Then** a payment is taken
- As a user when I have created my reservation I would like to receive a confirmation email so i can be assured i have ordered correctly - 3 Points
  - **Given** a valid booking **When** payment has completed **Then** a email is sent to the user

**EPIC:** A method to adminastrate the site - 40 Effort
<br/>
*feature:* Allow 3rd party advertisment to the site - 20 Effort
- As an admin I would like to apply a 3rd party advert into the home page so i can show trailers - 5 Points
  - **Given** a advert is to be shown **When** viewing the home screen **Then** a advert is shown
- As an admin I would like the adverts to be able to be controlled by a 3rd part advertisement provider - 5 Points
  - **Given** a new new live advert **When** viewing the advert **Then** the current advert is changed 

*feature:* admin area content magaement - 20 Effort
- As a Admin I would like an manage the content of the site through an administration portal - 8 Points
  - **Given** a CMS system **When** updating the site **Then** the site is updated
- As a Admin I would like to administrate the staff members that can use the site so i can update current staff members - 8 Points
  - **Given** a change to the staff **When** updating the staff list **Then** the list of staff users is updated
<br/>

**EPIC:** Allow staff members to manage bookings - 40 Effort
<br />
*feature:* Allow Staff member to manage user bookings - 20 Effort
- As a staff member i would like to be able to edit user bookins by a given order ID so i can change their booking - 8 Points
  - **Giving** A current booking **When** changing a booking **Then** the booking change is persisted
- As a staff member i would like to be able to search for a user booking by name so i can find a booking - 3 Points
  - **Given** a booking detail or a customers details **When** searching for a booking **Then** the booking for that customer us displayed
<br/>

Total effort of 76 story points. If we assume 5 point per day per developer = 3 weeks of just development time. Will need to acount for planning, testing, deploying and feedback.

Priority is describred by using the MoSCoW per release sechedule
- Must have
- Should have
- Could have
- Will not have


**Story point estimation guide:**

0.5 = 30 min work e.g. change text on webpage
1 = 1 hr work e.g. update Text, CSS and any JS hooks on a page
3 = half a day of work e.g. add a new form field onto a site
5 = day of work e.g. implement a new persisted form
8 = 1.5 days of work e.g. implement a new simple workflow
13 = 2-3 days of work e.g. implement a new feature set
20 = A feature detailing a set of stories
40 = An epic with an single feature set
