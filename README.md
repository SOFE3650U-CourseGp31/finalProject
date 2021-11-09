# SOFE3650U-CourseGp31 - Project Title: Airline Reservation System
### Table of Contents
1) [Project Description](###Project-Description)
2) [Group Members](###CourseGp31-|-Group-Members)
3) [Functional & Non-Functional Requirements](###Functional-&-Non-Functional-Requirements)
4) [Use Case Model](###Use-Case-Model)
5) [Quality Attributes](###Quality-Attributes)
6) [System Constraints](###System-Constraints)

### Project Description:
Vision Statement: To create a user friendly flight reservation website that will acclimate every type of user including novice users.

Scope: The reservation system will be presented in a website form that is straightforward and easily navigated. In doing so will allow customers to book a flight within minutes. The website needs to be presentable and pleasing on the eye in order to attract individuals looking to fly on vacation, businness, or personal reasons.

### CourseGp31 | Group Members
|Last Name|First Name|StudentID|
|:--------|:---------|:--------|
|Caguimbal|Lorenzo   |100555976|
|Casaclang|Roniel    |100755336|
|Olagunju |Charles   |100749818|
|Osuki    |Osasogie  |100748837|

### Functional & Non-Functional Requirements:
|ID|Functional Requirements|ID|Non-Functional Requirements|
|:---|:---|:---|:---|
|RQ-01|Record reservation|RQ-16|Accessibility: The website and user interface should be convenient for the users to comprehend, allowing them to navigate and access the website easily.|
|RQ-02|Record customer details(first and last name, phone number, email address)|RQ-17|Security: The website should be secured and users are able to have their privacy protected from other parties.|
|RQ-03|Associate booking with an account|RQ-18|Compatibility: In this sense, regardless of the system or device the customer is using the website should still retain its functionality.
|RQ-04|Generate unique confirmation number|RQ-19|Performance: Website should be fully optimized to enable the user to not have any delays or crashes while on the Reservation website.|
|RQ-05|Record airline and seat number|RQ-20|Availability: The website should be available for the user to see available flights regardless of the time.|
|RQ-06|Cancel bookings|
|RQ-07|Change and modify reservations|
|RQ-08|Display and change records of guests|
|RQ-09|Limit every account to a single user|
|RQ-10|Accept date and time to check availability of that particular date and time|
|RQ-11|Send out booking confirmation to the specified contact detail|
|RQ-12|Allow users to search and find the most relevant booking options (i.e first class, economy or coach class)|
|RQ-13|Calculate and display the airline charges|
|RQ-14|Record available and booked airlines|
|RQ-15|Allow users to filter airlines when searching|

### Use Case Model:
![alt text](https://github.com/SOFE3650U-CourseGp31/finalProject/blob/master/projectDeliverables2/Use%20Case%20Model.png "Use Code Model")

| Use Case      | Description  | 
| :------------- |:-------------|
| UC-1: Sign-Up / Login     | A user or administrator registers/logs into the system through the sign-up/login screen. |
| UC-2: Make a reservation      | A user makes a flight reservation, selecting the times, dates, passenger seats, travel class, destination and type of flight ticket. |
| UC-3: Edit a reservation | A user edits a reservation under their account. An admin edits a user's reservation.       |
| UC-4: Updates database | Airline server updates the database for every user activity and every information that is entered.    |
| UC-5: Limit every account to a single user | Airline server limits the user from registering the same email.    |
| UC-6: Search | A user or admin uses the search bar with a filter to search for destinations or airlines.    |
| UC-7: Access to every user account | An admin opens a user's account.   |


### Quality Attributes:
| ID | Quality Attribute | Scenario | Associated Use Case
|:---|:---|:---|:---|
| QA-1 | Accessibility   | The website is user-friendly and accessible. The UI allows any user to navigate the website easily and quickly make reservations. | UC-1, UC-3, UC-4, UC-6 & UC-7
| QA-2 | Security        | User logs into the system and makes changes to their account. The system has all changes documented and timed and also available for the user to see.| UC-5
| QA-3 | Compatibility   | User decides to use an Android device to make flight reservations and it is still functional as it is compatible with the device.| ALL
| QA-4 | Availability    | There is downtime in the regular operation of the system. The system is backed up and running in less than a minute.      | ALL
| QA-5 | Performance     | All services are 100% functional at all times.          | ALL

### System Constraints:
|ID|Constraint|
|:---|:---|
|CON-1| Accommodate for multiple users must be able to book a reservation / use the system simultaneously, automatically storing each sessions in the database|
|CON-2| Compatibility with desktop operating system (Windows, MacOS, Linux) |
|CON-3| Future support for mobile operating system (iOS, Android) |
|CON-4| System must respond quickly to request of information from database / servers. (transitions between forms, filtering of available flights, etc.) |
|CON-5| Network connections between user and servers should be consistent and reliable |
|CON-6| System must always be up to date with flight details (available flights, # of available seats, time of arrival/departure, etc.)
