# Testing

## Test Plan
TODO: Describe any manual and automated (unit) tests. Uniquely identify each test case. Include prerequisites and test data.

| Test case ID | Test Type | Description | Scenario |
| ------------ | --------- | ----------- | -------- |
| TF1 | UAT | The system shall display data for the user is in/ selects | When the user opens the page with area data, the information is displayed in a table |
| TF3 | UAT | The system shall allow employers to view their posted job adverts, and for job seekers to view said adverts. | The user opens the job adverts/home page, then all job adverts are displayed. |
| TNF1 | UAT | The system assumes a sensible default for user location | If the geolocation cannot be obtained, assume any ward |
| TNF3 | UAT | Works on Chrome and Safari, maybe firefox | The user opens the app in one of the 3 browsers, and no unique errors are encountered |
| TNF4 | UAT | Table/data is fetched in a reasonable time to the performance capabilities of the user's device | The user opens the app and doesn't have to wait too long for the data to load |

Test Runs
TODO: For each test described above, indicate the current status. 
Create a requirements traceability matrix to validate the completeness of the product.

| Use-Case ID | Requirement ID | Test Case | Status |
| ----------- | -------------- | --------- | ------ |
| UC1 | FR1 | Refer to TF1 Description | Pass; User can use a table in the menu and a map of the Bristol wards to see specific information to their area |
| UC2 | FR2 | The system shall allow employers to post job adverts, including the location of the job | Pass; the employers can add their jobs to the table in the menu with Ward, employer, job type and pay/hour information. Job seekers can then use the map to check the location of the job using the wards |
| UC2 | FR3 | Refer to TF3 Description | Pass; employers and employees can see the job adverts posted |
| UC1 | NFR1 | The system shall assume a sensible default for the user geolocation if there is none available | Fail; no geolocation data is required, the open data bristol map centers on the whole Bristol area |
| No use case| NFR2 | No security is required as all data is public | Pass; Jobcator does not have a log-in because all the data used is publicly available at Open Data Bristol |
| No use case | NFR3 | Works on Chrome, safari and Firefox | Pass; Jobcator works on Chrome, safari and firefox |
| UC1/UC2 | NFR4 | Table/data is fetched and displayed in a time reasonable to the performance capabilities of the device being used | Pass; the table data appears almost instantly when the website is loaded, the same for the ward information, the map takes a couple of seconds to load |
