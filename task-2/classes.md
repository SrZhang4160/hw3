# Task 2:
### ClassName: Organizer

Responsibilities:
* Create an Event
* Sell Tickets of an Event
* Provide SeatingMap

Collaborators:
* Event
* Ticket
* SeatingMap

### ClassName: Customer

Responsibilities:
* Browse Events
* Filter Events
* Select the number of Tickets
* Acquire SeatingPlan
* Select Seats
* Purchase Tickets

Collaborators:
* Event
* SeatingMap
* SeatingPlan
* Seat
* Ticket

### ClassName: Event

Responsibilities:
* Filter key words
* Location
* Time

Collaborators: None


### ClassName: Ticket

Responsibilities:
* Show correspongding Event
* Show correspongding Seat

Collaborators:
* Event
* Seat

### ClassName: SeatingMap

Responsibilities:
* Show a map of Seats

Collaborators:
* Seat

### ClassName: SeatingPlan

Responsibilities:
* Give seating plan

Collaborators:
* Seat
* SeatingMap

### ClassName: Seat

Responsibilities:
* Show Position
* Show availability of the seat

Collaborators: None

