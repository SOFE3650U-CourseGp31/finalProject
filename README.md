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
|:---:|:---|:---:|:---|
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
![alt text](projectDeliverables2/useCaseModel.png "Use Code Model")

| Use Case      | Description  | 
| ------------- |:-------------|
| UC-1: Login     | A user logs into the system through a login/password screen. Airline server tries to access user information from the database based on the input in the login/password screen. |
| UC-2: Record Reservation      | A user makes a flight reservation, selecting the times, dates, passenger seats, travel class, destination and type of flight ticket. These data will be stored in the database through the airline server.    |
| UC-3: Record customer details | A user enters his/her personal information such as first name, last name, passwords, etc.. which will be stored in the database through the airline server.     |
| UC-4: Associate booking with an account | The airline server links the user account to their reservations based on the unique IDs that are recorded in the database.     |
| UC-5: Generate a unique confirmation number | A unique confirmation is generated upon confirmation which will be stored in the database through the airline server.      |
| UC-6: Change and modify reservations | A user cancels their reservation. Any reservation changes in their account will be recorded in the database.       |
| UC-7: Display and change records of guests | A user displays and changes the number of passengers. Any changes made will be sent into the database through the airline server.    |
| UC-8: Limit every account to a single user | An administrator limits every account to a single user based on the registered email.      |
| UC-9: Accept date and time | A user selects date and time in the reservation page.    |
| UC-10: Confirm booking | A user confirms the booking after making the necessary selections from the reservation page.    |
| UC-11: Allow users to search | A user searches for a destination or an airline in their respective search bar. Calls the airline server to retrieve those information from the database.     |
| UC-12: Calculate and display airline charges |  A user displays and calculates the price after making a reservation. Prices vary depending on the selections made.     |
| UC-13: Record available and booked airlines | Airline server records booked passenger seats and sends it to the database. This record will be used to determine whether the airline has reached its maximum capacity.      |
| UC-14: Allow users to filter airlines when searching | A user selects various filters to narrow down search results for specific or available airlines.      |

### Quality Attributes:

### System Constraints:
|ID|Constraint|
|:---|:---|
|CON-1| Accommodate for multiple users must be able to book a reservation / use the system simultaneously, automatically storing each sessions in the database|
|CON-2| Compatibility with desktop operating system (Windows, MacOS, Linux) |
|CON-3| Future support for mobile operating system (iOS, Android) |
|CON-4| System must respond quickly to request of information from database / servers. (transitions between forms, filtering of available flights, etc.) |
|CON-5| Network connections between user and servers should be consistent and reliable |
|CON-6| System must always be up to date with flight details (available flights, # of available seats, time of arrival/departure, etc.)