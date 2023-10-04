<h1>Create Simple Dashboard in Splunk</h1>

<h2>Overview</h2>
Installed and configured Splunk Enterprise, a leading SIEM tool in log and data analysis. Configured Logs for ingestion, PQL splunk search, table and dashboard creation.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Splunk Search Processing Language (SPL) </b> 
- <b>Splunk Enterprise</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Install and log in to Splunk. Go to Settings and Data Inputs to set up which inputs you want to collect: <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/94e03895-3915-4c2a-b3ef-d480222733a9"/>
<br />
<br />
Edit Local event log c ollection since we will be  collecting events from this machine:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/bcebb9ab-f1ae-4a11-9dd3-90df07c324d4"/>
<br />
<br />
Select Application, Security, and System logs to be ingested into the tool: <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/5cf0f924-f8d6-41e6-833a-95b3160c92bf"/>
<br />
<br />
Successful event log collection creation for localhost:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/842220ee-f34d-4667-badb-818be8fcee8f"/>
<br />
<br />
In Search & Reporting, search "*" which retrieves all the events:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/abd70621-58ac-402f-83a2-3a126a9e2f45"/>
<br />
<br />
Clear the event log on this machine:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/a7ed58b4-8333-40f9-a073-6fc163655a1c"/>
<br />
<br />
Add elements from the "*" results to the search bar:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/31c2710c-322e-445b-91ac-f4be6f2ff9b7"/>
<br />
<br />
Modified search includes host, source, and event code data:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/7568f8a7-49ff-41df-b5ed-bfd3950582cf"/>
<br />
<br />
The clear log event is shown:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/2a19234a-7b7d-4df0-b1bf-aa2a7f304cdf"/>
<br />
<br />
Create a table to show the results of the query:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/edf6dd37-64ae-4126-8746-bc27a15fa8d6"/>
<br />
<br />
The table shows two instances in which the event manager had its log cleared:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/e7c7cc5f-2b8e-4479-9291-40dc61b99660"/>
<br />
<br />
Create a new dashboard:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/9d517511-208f-4226-94d0-58072a08d181"/>
<br />
<br />
Add a table to the dashboard:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/c602b2f9-c519-4088-a5d4-44d2fb5c89c0"/>
<br />
<br />
Use SPL to retrieve desired data and eliminate unnecessary columns:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/c30688b7-c04f-4ef4-8d88-1c8ea69f6ea9"/>
<br />
<br />
Add the table to the dashboard of Splunk:  <br/>
<img src="https://github.com/marthajsosa/SplunkSIEM/assets/146014829/10d935ae-e32a-42ef-97a5-c841b4df60bf"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
