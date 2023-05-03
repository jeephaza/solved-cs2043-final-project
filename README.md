Download Link: https://assignmentchef.com/product/solved-cs2043-final-project
<br>
For the final project, we were tasked with creatively identifying and implementing a solution to a complex problem that exists within the domain of ICT. It’s clear to anyone paying attention, our healthcare system is not sustainable. The possibility to predict diseases or to warn individuals of their progressions before it is a severe problem would help reduce strain on the health care system. To personalize a menu, measure the amount of activity with better accuracy, and finally, monitoring and advice on current health status would greatly impact the quality of life for those individuals with elevated care requirements.

Creating a healthcare monitoring system allowed us to work as an effective team to implement a software based solution that would deliver measurable value to the industry.

<h1>Overview of the System</h1>

Client – Upon purchasing a wearable device (eg.smart watch) user will upload personal data to be monitored and measured for self-improvement, health monitoring and medical analysis. User will be identified through a unique identification number and password to create account and assess own data. The wearable device will measure vitals and record physical data. There will be different options for users to subscribe to. High risk individuals such as diabetics or those with genetic disorders will be able to have their data closely monitored by their health care provider and have automatic alerts if vitals reports are concerning. In the event of a medical emergency, a health care professional will be able to access data off of the users device such as vitals, medical history, medications, allergies and blood type. Those wishing to have guidance for self improvement will subscribe to coaches for fitness and nutrition. Through that they will submit reports to have analyzed then receive feedback and modifications from their coaches. <sub> </sub>

System – Website and app connected to user’s wearable device. Device will measure physical data and store it with the client’s profile accessible through a website. User friendly interface for client to upload and monitor data. Interface for healthcare professionals to connect to in the event of urgent medical care. Available connection for fitness and nutrition coaches to check progress and submit changes to recommendations. System will notify health care professionals of changes that may be concerning. Alerts will be issued to the user if blood sugar or heart rates are at dangerous levels. It is required to keep medical information and personal information separate. The system will include a specialized database that allows the storage of dynamic information for clients.  This type of system is targeted at many stakeholders. Users ca be split into various categories including:

<ul>

 <li>Health care professionalsFitness motivated individuals</li>

 <li></li>

 <li>Diabetics</li>

 <li>Individuals with genetic disorders</li>

 <li>Personal Trainers</li>

 <li>High risk individuals</li>

 <li>Nutritionists</li>

</ul>




Due to time constraints, we decided to use the Agile approach for this project. The first phase consisted of finding the right functional and non-functional system requirements along with a large set of target actors. The functional system requirements we outlined as team (refer to table 1 below). Understanding the requirements allowed us to focus on the effective implementation of our system. Although with the time available we were only able to implement a small portion of what the final system would be, we have an outline to guide future development while expecting it to be subject to more changes. We did spend a large chunk of time coping with the requirements specification (we specified some requirements that we did not assess later) as well as the system architecture, leaving us with little time for the implementation phase. However, we managed to build a small prototype for both the website and the Android Application.




A gantt chart was created so we could organize our schedule and progress (refer to figure 1 below). Then, an array of use-case scenarios was defined following an assessment of the viewpoints of all stakeholders. Through our system, various users will be able to communicate about all their health and wellness concerns. We were able to demonstrate these connections through our use cases (refer to table 2 below). These scenarios were curated and merged to provide us with some grounding for the implementation and testing of our first prototypes. A use care diagram was created for a visual representation of users interacting with the database (refer to figure 2 below). Creating a class diagram was chosen to illustrate how different entities would work together (refer to figure 3). After creating diagrams to visualize the design, we were able to begin the construction of our system.




Table 1: Functional System Requirements of health monitoring system listed with description of requirement and the priority rating on a scale of 1-5.

<table width="624">

 <tbody>

  <tr>

   <td width="208"> </td>

   <td width="208">Description</td>

   <td width="208">Priority</td>

  </tr>

  <tr>

   <td width="208">REQ-1</td>

   <td width="208">The system should allow the user to create his own profile and modify it</td>

   <td width="208">5</td>

  </tr>

  <tr>

   <td width="208">REQ-2</td>

   <td width="208">The system should be able to store the personal health data uploaded by users from anymachine(computer/mobile) into a database</td>

   <td width="208">5</td>

  </tr>

  <tr>

   <td width="208">REQ-3</td>

   <td width="208">The system should provide 4 types of accounts: one for health professionals, one for personal coaches and nutritionists, one for regular users and one for users at risk (people with diabetes, genetic conditions, chronic diseases…)</td>

   <td width="208">3</td>

  </tr>

  <tr>

   <td width="208">REQ-4 </td>

   <td width="208">For the regular users account, the system should have these features:Fitness monitoringDietary guidance</td>

   <td width="208">2</td>

  </tr>

 </tbody>

</table>




<table width="624">

 <tbody>

  <tr>

   <td width="208"> </td>

   <td width="208">Health monitoring –</td>

   <td width="208"> </td>

  </tr>

  <tr>

   <td width="208">REQ-5</td>

   <td width="208">Connecting actors to the user. Allowing the diverse types of professionals to modify plans and provide recommendations to users.</td>

   <td width="208">2</td>

  </tr>

  <tr>

   <td width="208">REQ-6</td>

   <td width="208">System will allow for user’s vital information to be accessed by health care professional in the event of a medical emergency</td>

   <td width="208">5</td>

  </tr>

  <tr>

   <td width="208">REQ-7</td>

   <td width="208">System will monitor vitals of user and send alert when there is a dramatic change in blood sugars or heart rate</td>

   <td width="208">3   </td>

  </tr>

  <tr>

   <td width="208">REQ-8 </td>

   <td width="208">Access personal data about the client health presented as formalized electronic medical records that enable displaying the current integral evaluation of the health state</td>

   <td width="208">2</td>

  </tr>

  <tr>

   <td width="208">REQ-9 </td>

   <td width="208">The system will include a specialized database that allows storage of dynamic information of clients. </td>

   <td width="208">1</td>

  </tr>

  <tr>

   <td width="208">REQ-10 </td>

   <td width="208">System will connect to other companies’ technologies that monitor heart rate, blood pressure and blood sugar</td>

   <td width="208">2</td>

  </tr>

  <tr>

   <td width="208">REQ-11</td>

   <td width="208">Encapsulation to ensure only authorized individuals access sensitive information </td>

   <td width="208">1</td>

  </tr>

  <tr>

   <td width="208">REQ-12</td>

   <td width="208">User interface for webapp/website should be user-friendly and intuitive</td>

   <td width="208">3</td>

  </tr>

  <tr>

   <td width="208">REQ-13</td>

   <td width="208">User interface for Android app should be user-friendly and intuitive</td>

   <td width="208">3</td>

  </tr>

  <tr>

   <td width="208">REQ-14</td>

   <td width="208">System should not give access to the main database to regular users.</td>

   <td width="208">4</td>

  </tr>

  <tr>

   <td width="208">REQ-15</td>

   <td width="208">System should not allow the user to access the account for another user</td>

   <td width="208">4</td>

  </tr>

  <tr>

   <td width="208">REQ-16</td>

   <td width="208">A maximum of 2 superusers are allowed.</td>

   <td width="208">2</td>

  </tr>

 </tbody>

</table>







Figure 1: Gantt chart to monitor scheduling and progress




Table 2: Use-case scenarios

<table width="624">

 <tbody>

  <tr>

   <td width="208"> </td>

   <td width="208"> </td>

   <td width="208"> </td>

  </tr>

  <tr>

   <td width="208">Client creating profile</td>

   <td width="208">Allows user to create his/her personal profile and modify its access/information</td>

   <td width="208">REQ-1</td>

  </tr>

  <tr>

   <td width="208">Health care professional</td>

   <td width="208">Allow health care professionals to monitor high risk patients, or patients with different disorders to make necessary changes to optimize health of patient.</td>

   <td width="208">REQ-5</td>

  </tr>

  <tr>

   <td width="208">Healthcare professional (In Emergency situation)</td>

   <td width="208">Access vitals of patient for emergency treatment</td>

   <td width="208">REQ-6</td>

  </tr>

  <tr>

   <td width="208">Fitness/ nutrition coach</td>

   <td width="208">Access client’s reports then provide feedback</td>

   <td width="208">REQ-8</td>

  </tr>

  <tr>

   <td width="208">User</td>

   <td width="208">Connecting to database to review and submit changes</td>

   <td width="208">REQ-14</td>

  </tr>

 </tbody>

</table>

<h2>Use Case                      Description                Requirement satisfied</h2>










Figure 2: Use case diagram to represent users interacting with database.




Figure 3: Class diagram to illustrate the desired operation of the system.




Due to a lack of experience in the industry, Java was the chosen language of development. Skeleton classes were coded to begin the development process. Sockets were chosen to implement messaging between users although, with further information, a different decision would have been made. A socket represents a connection for communication between two users (refer to figure 3). Multiple individuals in client/server or distributed systems can simultaneously communicate with a single Web server. Multiple sockets are required to do this. The socket’s flow of events starts with a connection-oriented client-to-server model, the socket on the server process waits for requests from a client. To do this, the server first establishes (binds) an address that clients can use to find the server. When the address is established, the server waits for clients to request a service. The client-to-server data exchange takes place when a client connects to the server through a socket. The server performs the client’s request and sends the reply back to the client.







Figure 3: Communication diagram to represent sockets




<h1>Health Monitoring System Website</h1>

Our website was locally developed using the Django framework, which is web framework for python, along with some HTML, bootstrap, and sqlite3 for the database. Bootstrap was implemented using the hosted bootstrap CDN, and custom forms were included to the Django Project. The user can explore the website through the navigation bar at the top ribbon.

The website allows the user to perform the following set of functionalities:

<ul>

 <li>A potential user can create a unique profile using his/her first and last name, email, username, and user-defined password. The password should follow the requirements presented on the register page and the user can create his account only if the security requirements are followed</li>

 <li>A user can login to his/her created account without any limitations or constraints, but the same user cannot access another user’s profile</li>

 <li>When the user is logged in, he/she can change the password associated with the account (following the same security requirements as in the registration phase) if the old password is provided.</li>

 <li>In the edit profile section, a logged-in user can alter his/her username, first and last name, as well as the email address. At the bottom of the page, a user can click on the link which will redirect to the change password page.</li>

 <li>An upload feature is added to the registered user’s page. The user can upload his/her medical data using this feature (files are hosted locally).</li>

</ul>




<ul>

 <li>The Django framework provides an admin space where a superuser can monitor the number of users and either add a new user or delete an existing user. The admin can also track the uploaded files and choose to keep or delete these files.</li>

</ul>

Figure: Django Admin Users Dashboard

Figure: Deleting Documents using The Admin Functionality

<h2>Design</h2>

In the design part, we decided to use two forms of web and Android software to develop our program. The following is the Android software design process. We used Android Studio to develop. First, we designed the application login interface. We used some simple codes to create the input account, password and login and registration buttons for the login interface.

Here is code for login interface

After that, create a registration interface, enter your name, email and password, and sign in up button. Here is code for registration interface.

Then, create a profile interface to save user’s input information. Here is code for profile

After that, we need to create some elements such as interface color and interface shape and create a main interface slide to include the login interface. Here are three interface display

We create three java classes to implement those three interfaces and those three classes are controlled by main class. Below is the code of the three classes

Testing

The next step is to test these three interfaces (after 3 tests and modify some bugs) the compiler has no errors and can run normally. Running the simulator, open the application successfully and try to log in and register the test. The result of the operation is: the program cannot detect the input and cannot jump to the profile interface. This problem cannot be fixed for technical reasons. However, we believe that we can solve this problem by further studying Android applications.

With a system associated with human health, the risks are severe. Our system would be subject to rigorous testing before being released. Some testing could include:

<ul>

 <li>Test connectivity and functionalCheck encapsulation by attemptingity of each use caseto access medical information from coach perspective</li>

 <li></li>

 <li>Ensure client is able to access multiple recommendations and requirements at the same timeInput altered data from external monitors to verify the system displays changes in real</li>

 <li></li>

</ul>

time

<ul>

 <li>Monitor healthy client with a duplicate account to ensure there are no discrepancies between accounts</li>

</ul>

Risks involved in this type of system include:

<ul>

 <li>Bugs providinSecurity breach affecting client privacyg inaccurate results</li>

 <li></li>

 <li>Trainability of health care professionals required to operate the system</li>

 <li>Relying on other technology (wearable device, Dexcom) to connect properly to our software</li>

</ul>

Future evolution of our system would be a lengthy process and the following would need to be considered:

<ul>

 <li>Enlisting guidance from professionals to determine estimated development costsExpanding classes to include various types of health care professionals with different</li>

 <li></li>

</ul>

requirementsMeeting with representatives who have developed physical monitoring devices

<ul>

 <li></li>

 <li>Consulting with health care professionals and coaches to determine the most affective user interface for their applicationImplementing a functioning system s is subject to rigorous testing</li>

 <li></li>

</ul>




This project allowed us to participate in all the development phases of a software system.  We were better able to understand what is involved in requirements, analysis, design, construction, testing and documentation. Our goal was to take the specific information we learned in CS2043 and implement it in numerous ways. Initially we developed our software management plan. Deciding what we wanted to create and who would be responsible for what was the beginning of making and defending sound engineering decisions. Although, as we progressed some of those decisions were altered to better suit our finished product. Project management was the key to stay connected as a team and make decisions on what we wanted to do and how. We achieved most goals through planning, preparation, results and evaluation, contributing to achieving our strategic goals.