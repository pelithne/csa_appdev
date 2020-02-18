# Office Socialism
Comtoso has recently moved their regional HQ to a new location. The HR Department is wants to maximize ROI of the new, central office location, and accommodate the need for co-workers to meet inside and outside the office. As a step to improve overall health and creativity for its employees, Comtoso wants to launch an application that:

 * Promotes physical activity in the workplace and simplifies planning to make health a part of every employee's schedule.
 * Helps employees meet colleagues in the new environment, both for work-related and social activities.

Comtoso's HR department believes that by deploying this solution to their employees, they will be able to increase productivity of their workforce, both through boosting creativity as well as reducing the total number of sick days.

## Functional requirements
* The location of every employee needs to be tracked and updated every 5 minutes. 
* When an employee arrives at an office location, an alert should be triggered
* Employees should be able to subscribe to alerts for other employees using role filters (i.e. all CSA:s)
* Using the app, employee should be able to schedule social activities:
	* **Work-out:** Employees should be able to organize workouts that fit with their work schedule. It should be possible to choose different types of workouts (i.e. weightlifting, running, yoga etc). The service should also include an 'inspire me' option where a list of group training activities are retrieved from nearby gyms. Additionally, Comtoso wants their employees to be prompted after a certain amount of inactivity, with suggestions of activities that could fit their work schedule (for example a 20 minute walk).
	* **Lunch:** Employees should be able to send lunch requests to all colleagues that have arrived at a certain location (i.e. the Stockholm office). 
	* **After work:** Same as lunch, but with suggestions for happy hour
	* It should be possible for other employees to join an activity already scheduled by others
* To follow up on the progress of its initiative, Comtoso HR wants a report showing the following key metrics:
	* Number of activities scheduled per week
	* Average number of employees per activity
	* Total amount of time spent on activities
	* Average number of sick days per week

## Non-functional requirements:
* Must be able to scale beyond 100,000tps for location tracking of Comtoso's global workforce
* Must be highly performant with 99% of requests taking no more than 200ms.
* Must be highly resilient and support an availability target of greater than 99.99%.
* Must be globally available and capable of scaling to new regions with relative ease.
* Must be simple to maintain the same code base should used for both mobile and web apps

