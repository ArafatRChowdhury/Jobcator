# Requirements

## User Needs

### User stories
1. As a job seeker, I want to find jobs by ward and industry, so I know where to look for a job in my industry of interest.
2. As an employer, I want to be able to attract employees to my company/business


### Actors
1. Job seekers
2. Employers

### Use Cases

| UC1 (Jaime's use case) | Find jobs by users area | 
| -------------------------------------- | ------------------- |
| **Description** | As someone in need of a job, I want to see what industry jobs are available in my area |
| **Actors** | Person that is in search of a job |
| **Assumptions** | Browser supports geolocation</td></tr>
| **Steps** | 1. Request permission to access user location.<br>2. On request, give permission for user location.<br>3. View table for the user's area.|
| **Variations** | 2. Browser does not support geolocation |
| **Non-functional** | NFR4: Data is fetched in a reasonable time. |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC2 (Arafat's use case) | Publish job adverts | 
| -------------------------------------- | ------------------- |
| **Description** | Job seekers will need someone to give them employment opportunities so employers will be able to upload job adverts |
| **Actors** | Employer looking for employees|
| **Assumptions** | None</td></tr>
| **Steps** | 1. Log-in to the app as an employer<br>2. Make a job advert specifying what the job is about, salary, benefits, location and job type<br>3. Publish the job advert|
| **Variations** | n/a |
| **Non-functional** | TODO: OPTIONAL - List of non-functional requirements that the use case must meet. |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |



![Insert your Use-Case Diagram Here](images/Use-case-diagram.png)

## Software Requirements Specification
### Functional requirements

- FR1: The system shall display the data for the area the user is in/selects (UC1 and UC2)

- FR2: The system shall allow employers to post job adverts, including the location of the job

- FR3: The system shall allow employers to view their posted job adverts, and for job seekers to view said adverts.

### Non-Functional Requirements

Indicate which UC the requirement comes from.

- NFR1: The system shall assume a sensible default for the user geolocation if there is none available, derived from UC1 and UC3 (Reliability)

- NFR2: No security is required as all data is public (Security)

- NFR3: Works on chrome and safari, maybe firefox (Compatability)

- NFR4: Table/data is fetched and displayed in a time reasonable to the performance capabilities of the device being used (Performance efficiency)
