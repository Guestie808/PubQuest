# Testing

## Test Plan
The following test cases were done to verify the functionality of the key features within the application, including the search functionality, location-based venue display, and navigation to the Plan a Crawl page. Testing was performed manually by interacting with the system through the user interface. The results of each test case, including prerequisites and test data used, are documented in the table below.

| Test-Case ID | Test Description | Page Location |  Prerequisites | Test Data | Status | Reason |
| ------------ | ---------------- | ------------- | -------------- | --------- | ------ | ------ |
| TC1 | Apply filter to show available venues | filter.html | User is on filter page | Filter: "Nightclubs" | Pass | Filter displays correct results |
| TC2 | Toggle filter off | filter.html | Filter is currently applied | Click filter again | Pass | Results reset correctly |
| TC3 | Multiple filters at once | filter.html | User is on filter page | Select 2 filters | Fail | Feature not implemented yet |
| TC4 | Search for a venue using the search bar | index.html, filter.html, map.html, plan.html | Application is running | Search term: Name of venue e.g. "Villager" | Pass | Relevant venues displayed in results |
| TC5 | Click search button with empty search field | index.html, filter.html, map.html, plan.html | Application is running | No input | Pass | All venues are displayed when search field is empty |
| TC6 | View local venues with location permission allowed | map.html | Browser location services enabled | User clicks "Allow location" | Pass | Map displays nearby venues |
| TC7 | View local venues with location permission denied | map.html | Browser location services enabled | User clicks "Deny location" | Pass | Map still loads without user location |
| TC8 | Navigate to Plan a Crawl page | plan.html | Application is running | Click "Plan a Crawl" | Fail / Incomplete | Page loads but feature not yet implemented |

The table below shows the Requirements Traceability Matrix, which links each functional and non-functional requirement to the test cases that were carried out. This helps demonstrate that the key features of the system have been tested and shows which requirements have been successfully implemented, as well as those that are still incomplete in the current version of the application.

| Use-Case ID | Requirement ID | Test Case | Status |
|-------------|---------------|-----------|---------|
| UC1 | FR1 | N/A | Incomplete |
| UC2 | FR2 | N/A | Incomplete |
| UC3 | FR3 | N/A | Incomplete |
| UC3 | FR4 | N/A | Incomplete |
| UC4 | FR5 | N/A | Incomplete |
| UC4, UC5 | FR6 | N/A | Incomplete |
| UC6 | FR7 | TC3 | Pass |
| UC7 | FR8 | TC5 | Incomplete |
| UC8 | FR9 | N/A | Incomplete |
| UC8 | FR10 | N/A | Incomplete |
| UC1 | NFR1 | N/A | Incomplete |
| UC1, UC3 | NFR2 | N/A | Incomplete |
| UC4 | NFR3 | N/A | Incomplete |
| UC6, UC7, UC8 | NFR4 | TC3 | Pass |
| UC5 | NFR5 | N/A | Incomplete |
| UC5, UC6, UC7, UC8 | NFR6 | TC3 | Pass |
