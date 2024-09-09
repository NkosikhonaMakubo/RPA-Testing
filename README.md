# CMPG 323 Project 4 - User Acceptance Testing Automation
## Project Overview
This project automates the User Acceptance Testing (UAT) process for the NWU Tech Trends Telemetry Portal. The testing ensures that CRUD (Create, Read, Update, Delete) functionality for Clients and Projects is accurately validated against test data provided in an Excel file. The solution is developed using UiPath and deployed to UiPath Orchestrator for automated execution.
## Objectives
* Automate UAT processes using Robotic Process Automation (RPA) UiPath.
* Test the Create, Read, Update, and Delete functionality for Clients and Projects.
* Log the test results (TRUE/FALSE) in an Excel file.
* Host the automation process on UiPath Orchestrator for deployment.
## Prerequisites
Before running this project, ensure you have:

1. UiPath Studio Community Edition installed.
2. An account on UiPath Orchestrator.
3. Access to the NWU Tech Trends Telemetry Portal [here](https://techtrendstelemetryportal.azurewebsites.net/).
4. The Excel file containing the test data for Clients and Projects.
## Project Structure
* **Automation Process:** The main UiPath automation is responsible for reading test data, executing UI interactions, and verifying test results.
* **Excel File:** Contains input data for Clients and Projects, as well as a results column to log whether tests passed or failed.
* **ReadMe.md:** This document provides instructions on how to use the automation.
## Features
* **Client CRUD Testing:** Tests the creation, reading, updating, and deletion of Clients.
* **Project CRUD Testing:** Tests the creation, reading, updating, and deletion of Projects.
* **Excel Integration:** Reads input test data from Excel and logs test results.
* **Automated Deployment:** Hosted on UiPath Orchestrator for scheduled or on-demand runs.
## How to Use the Automation
### Step 1: Clone the Repository
1. Clone this GitHub repository to your local machine.
### Step 2: Open in UiPath Studio
1. Open UiPath Studio.
2. Import the UiPath project by navigating to the cloned folder.
### Step 3: Prepare the Excel File
1. Ensure that the Excel file containing test data (for Clients and Projects) is correctly formatted.
2. The Excel file should contain the following columns:
    -  ClientName, DateOnboarded, etc. for Clients.
    -  ProjectName, ProjectDescription, ProjectStatus, etc. for Projects.
### Step 4: Running the Automation
1. To run the automation locally:
    - Open the project in UiPath Studio.
    - Click on "Run" to execute the process.
2. To run the automation via UiPath Orchestrator:
    - Navigate to your UiPath Orchestrator dashboard.
    - Select the automation process and trigger a new job.
### Step 5: View Test Results
* Once the automation completes, open the Excel file to view the test results.
* A "Test Passed" column will show TRUE or FALSE depending on whether the tests were successful.
## References
1. YouTube. (n.d.). 14 September weekly virtual class Automation introduction. [online] Available at: https://www.youtube.com/watch?v=wi18JuLhZ74 [Accessed 3 Sep. 2024].
2. YouTube. (n.d.). UiPath - How To Publish Process To Orchestrator (Tutorial). [online] Available at: https://www.youtube.com/watch?v=TT3cgpWutD4 [Accessed 7 Sep. 2024].
3. Youtube. (n.d.). 03 October Project 4 Explained. [online] Available at: https://www.youtube.com/watch?v=5s1-p1okZoc [Accessed 6 Sep. 2024].
4. cloud.contentraven.com. (n.d.). Introduction to RPA and Automation. [online] Available at: https://academy.uipath.com/courses/introduction-to-rpa-and-automation [Accessed 4 Sep. 2024].
5. UiPath Studio. (n.d.). UI Automation. [online] Available at: https://docs.uipath.com/studio/docs/ui-automation [Accessed 3 Sep. 2024].
6. Boboc, M. (n.d.). Excel Automation Tutorial - DataTables Automation | UiPath. [online] www.uipath.com. Available at: https://www.uipath.com/learning/video-tutorials/excel-datatables-automation [Accessed 7 Sep. 2024].
7. Marcelo Cruz (2021). Write data on Excel - UiPath RPA Tutorial. [online] YouTube. Available at: https://www.youtube.com/watch?v=ABE-jCmHye4 [Accessed 4 Sep. 2024].
8. UiPath by Sujitha (2022). Excel Automation | UiPath Tutorials | Use Application Scope | Excel Process Scope Example. [online] YouTube. Available at: https://www.youtube.com/watch?v=Ow6bJI4prbM [Accessed 6 Sep. 2024].
9. Anders Jensen (2020). How to extract Web Data to Excel with UiPath - Full Tutorial. [online] YouTube. Available at: https://www.youtube.com/watch?v=VSTS-Xg1IIA [Accessed 2 Sep. 2024].
10. Anders Jensen (2020). UiPath | How to automate Excel and work with Data Tables | Tutorial. [online] YouTube. Available at: https://www.youtube.com/watch?v=E9GUL53V3-E [Accessed 7 Sep. 2024].
11. Anders Jensen (2020). UiPath | How to change the value of cells and columns in Excel | Guide. [online] YouTube. Available at: https://www.youtube.com/watch?v=bxX7w5PVOp8&list=PLXXz88_TPiHp_1N1pRURUpXnEt_quLyag&index=2 [Accessed 7 Sep. 2024].
12. Anders Jensen (2020). UiPath - How to add data to a new Excel column - Full Tutorial. [online] YouTube. Available at: https://www.youtube.com/watch?v=DTKyWrgDDDg&list=PLXXz88_TPiHp_1N1pRURUpXnEt_quLyag&index=3 [Accessed 7 Sep. 2024].
13. Anders Jensen (2020). UiPath | How to Read Excel Data, do an Online Search and write the result in the next Column | Guide. [online] YouTube. Available at: https://www.youtube.com/watch?v=9HxtyuAiPTk&list=PLXXz88_TPiHp_1N1pRURUpXnEt_quLyag&index=4 [Accessed 7 Sep. 2024].
14. YouTube. (n.d.). #Uipath #Exceldata #datatable Uipath : How to read excel data and store into Data table. [online] Available at: https://www.youtube.com/watch?v=5r1cBumKSi4 [Accessed 6 Sep. 2024].
15. UIpath RPA Learners (2022). UiPath: How to Combine/Concatenate Strings | UiPath For Beginners | UiPathRPA. [online] YouTube. Available at: https://www.youtube.com/watch?v=dX3nRztRCvQ [Accessed 8 Sep. 2024].
16. UIpath RPA Learners (2022). UiPath: What is Array | How to use Array in Uipath | With Example. [online] YouTube. Available at: https://www.youtube.com/watch?v=zqOhWV_bpgU [Accessed 8 Sep. 2024].
17. UiPath RPA (2018). UiPath Array Variable | String []Variable | Types of UiPath Variable | UiPathRPA. [online] YouTube. Available at: https://www.youtube.com/watch?v=qZduW3Gaz8k [Accessed 7 Sep. 2024].
18. Wikipedia. (2021). UiPath. [online] Available at: https://en.wikipedia.org/wiki/UiPath [Accessed 2 Sep. 2024].
19. Uipath.com. (2023). Available at: https://docs.uipath.com/orchestrator/automation-cloud/latest [Accessed 5 Sep. 2024].
20. Tutorials by Mukesh Kala (2022). What is UiPath Orchestrator | Overview | Importance | Capabilities | Beginners. [online] YouTube. Available at: https://www.youtube.com/watch?v=MVEiFUdEJ8U [Accessed 6 Sep. 2024].
21. YouTube. (n.d.). How Do I Publish UiPath Project Locally and Upload it to Orchestrator | Export UiPath Project. [online] Available at: https://www.youtube.com/watch?v=0PGvblwopdw [Accessed 8 Sep. 2024].
