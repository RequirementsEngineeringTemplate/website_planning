# Use Cases for project

## 001-0001: Potential Student using website for tasks available to them. 
**Primary Actors**: *Potential Student, Unregistered Student, New Student*
**Secondary Actor**: *Admissions*

**Preconditions:** *New students must register with site to login. Potential students should reach site due to linked advertisements or partnerships, admission webpage, a web search, search through website search function.*
1. Student will Login to site using Future Eagle Account
2. Student will select from options of the main menu:
    - Request Information
    - Event Registration
    - Apply for Enrollment
    - Check Application
3.  If Request Information or Event Registration is select the site will load the appropriate secondary site for completion of task.
4.  If Apply for Enrollment is selected the site shall load the application page for completion
    - Upon completion and submission of application page the student will be redirect to main menu (2)
5.  If Check Application is selected
    - The application status will be displayed for student with option to return to main menu after viewing

**Alternate Paths:**
1. Student has not registered for account, link to "register for university" will be displayed for student to register
    - No parts of the student applicaiton process can be accessed without login
2. Check Application is selected with no application found, then student will be redirected to Apply for Enrollment page.
3. Student forgot password
    - Link to "Forgot Password" will be provided on login page with instructions
    - If no username is found by system Link will direct to "Register Account" instead
4. Website cannot validate password/username due to validation system not working or loading
    - Notify user of condition and suggest they try at later time or contact admissions directly through other means.
5. Website cannot validate username/password and user has attempted more than 5 times
    - Notify and direct user to contact ITS for further assistance.

**Postcondition:** *User waiting on event, information, or application status. Or has recieved application status and moved to Admissions for enrollment or follow-up options.*

**Linked Use-Casses**: 200-0001, Application Check; 200-0002: Information Packet Requests; 200-0003, Event Scheduling; 001-0010, Enrollment; 003-0025, ClickPath Tracking
## Summary
Potential students are an essiential factor for running a university and attracting them ensures we are able to continue operating. To facilitate this, we must ensure those accessing our website with the goal of requesting information on the college or registering for our outreach, community, and enrollment events are able to quickly access these parts of the website. More importantly, any student ready to apply or checking their application status should have as near a direct path as possible to the application page to ensure their continued participation and full enrollment. This use-case focuses on the interactions needed for a potential student to login and access all the features available to them - particularly focusing on applying for the university and checking the status of the application through the website.

Any potential student who arrives at the main website and then navigates to the login page or arrives at login page via a direct link will be required to login to the site for full access. If they are a new student, then the website will provide information (on the same login page) on registering for an account and provided links directly to the registration page. Once registered, the student would then be able to login and either:

  1. Apply for the university or check the status of an application
  2. Register for Admission and other events
  3. Request information be sent in paper or electronic form to them

The main menu page shall link and securely share session information with our partner networks that handle information requests and event registrations. For applications, it will check for an application submission and if one is found provide links to check it. If no submission is found, the student will be provided links to the application page where they can complete the application process. The applicaiton page should validate all information being submitted to ensure required fields are correctly filled out before allowing the student to submit their application and, if successfully submitted, notify the user of the success before returning to the main menu page.
