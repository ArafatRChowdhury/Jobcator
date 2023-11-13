# Requirements

## User Needs

### User stories
TODO: Write brief user stories to explain how various actors would interact with the system to accomplish a goal.
    Express these in the form from agile development:- As a (role) I want (goal) so that (benefit).
#### 1. As a job seeker, I want to find jobs by ward and industry, so I know where to look for a job in my industry of interest.
#### 2. As a manager of a company, I want to be able to find employees who might want to work for my company.


### Actors
TODO: List and describe the actors/users for this product.
#### 1. Job seekers
#### 2. Company managers
#### 3. Employers

### Use Cases
TODO: Describe each use case (at least one per team member).
    Give each use case a unique ID, e.g. UC1, UC2, ...
    Summarise these using the use-case template below.

| UC1 | Find jobs by users area | 
| -------------------------------------- | ------------------- |
| **Description** | As someone in need of a job, I want to see what industry jobs are available in my area |
| **Actors** | Person that is in search of a job |
| **Assumptions** | Browser supports geolocation</td></tr>
| **Steps** | 1. Request permission to access user location.<br>2. On request, give permission for user location.<br>3. View table for the user's area.|
| **Variations** | 2. Browser does not support geolocation |
| **Non-functional** | TODO: OPTIONAL - List of non-functional requirements that the use case must meet. |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC2 | Publish job adverts | 
| -------------------------------------- | ------------------- |
| **Description** | Job seekers will need someone to give them employment opportunities so employers will be able to upload job adverts |
| **Actors** | Employer looking for employees|
| **Assumptions** | None</td></tr>
| **Steps** | 1. Log-in to the app as an employer<br>2. Make a job advert specifying what the job is about, salary, benefits, location and job type<br>3. Publish the job advert|
| **Variations** | n/a |
| **Non-functional** | TODO: OPTIONAL - List of non-functional requirements that the use case must meet. |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC1 | Find jobs by selected area | 
| -------------------------------------- | ------------------- |
| **Description** | As someone in need of a job, I want to see what industry jobs are available in a selected area |
| **Actors** | Person that is in search of a job |
| **Assumptions** | Browser supports geolocation</td></tr>
| **Steps** | 1. Opt to choose which area's table to view<br>2. View table of selected area|
| **Variations** | n/a |
| **Non-functional** | TODO: OPTIONAL - List of non-functional requirements that the use case must meet. |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |



TODO: Your Use-Case diagram should include all use-cases.

![Insert your Use-Case Diagram Here](images/use-case.png)

## Software Requirements Specification
### Functional requirements
TODO: create a list of functional requirements. 
    e.g. "The system shall ..."
    Give each functional requirement a unique ID. e.g. FR1, FR2, ...
    Indicate which UC the requirement comes from.

FR1: The system shall display the data for the area the user is in/selects (UC1 and UC2)


### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

Indicate which UC the requirement comes from.
