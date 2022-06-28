# Travel-Management
This is a C Console Application that manages the main tasks of a TRAVEL AGENCY. </br>
![Capture](https://user-images.githubusercontent.com/59179174/176245040-fe518457-4c71-4fe1-a8fd-72b536d0df80.PNG)
This project is divided into two main parts:
1. Part I: The management of the agency's trips. To facilitate the tasks, a line i in the different tables characterizing a TRAVEL (mentioned in the following slide) concerns the
information of a single traveler. A traveler can have several trips. For each trip, the customer is given the possibility to choose if he travels alone or in a group.
</br>Each TRIP is characterized by :
  * Identifier of a reservation for a trip
  * Passport number of the traveler
  * Traveler's name
  * Traveler's Date of Birth (if applicable)
  * Date of departure
  * Arrival date
  * City of destination
  * Country of destination
  * InGroup (True/False)
  * Group number 
</br></br> A GROUP is characterized by :
  * Identifier
  * Departure date
  * Arrival date
  * City of destination
  * Country of destination
  * Number of travelers assigned to this group (maximum 15)
</br></br> If it is a trip of a single client :
To create a new trip you need:
  * When the customer arrives, the application displays all his previous trips.
  * If it is a new customer, you must enter all his details (passport number, name and date of birth).
  * Choose a destination (city and country).
  * Choose a departure date and a return date
</br></br>If it is a group tour:
  * The same features of a single person trip must be provided. In addition, the assignment to groups must be managed.
  * Before selecting a group, the rows of the tables characterizing the groups.
  * Each group can contain a maximum of 15 passengers.
  * The user is given the possibility to choose a group if the maximum number of the maximum number of passengers assigned to that group has not yet been reached.
![Capture1](https://user-images.githubusercontent.com/59179174/176247072-bb289c74-40e7-41bb-9043-1dd24719101a.PNG)
![Capture2](https://user-images.githubusercontent.com/59179174/176247088-869c956b-25bd-43de-954b-22548aa218d7.PNG)
![Capture4](https://user-images.githubusercontent.com/59179174/176247095-86a0d0e4-1466-4b46-919f-aa9f30ea3dbb.PNG)

2. Part II: The calculation of statistics for the agency.
We now propose to conduct a statistical study that may be useful for the agency's be useful to the agency's leaders in the short and medium term. This study consists of finding and displaying the results of a number of queries that involve existing data. To manage the age ranges of the travelers in this part, we create a new AGES table that calculates these values in terms of years using the date of birth matrix and the actual system's date as shown below:
![Capture6](https://user-images.githubusercontent.com/59179174/176247434-9090c7a7-39c1-4423-af47-324cd29e24c7.PNG)
![Capture8](https://user-images.githubusercontent.com/59179174/176247443-40c8086c-5446-4362-9ed7-41313db869f2.PNG)
