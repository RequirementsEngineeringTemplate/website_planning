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

**Linked Use-Casses**: 200-0001, Application Check; 200-0002: Information Packet Requests; 200-0003, Event Scheduling; 001-0010, Enrollment
