# JunctionMaverick

At Team Maverick, we are proposing a streamlined status reporting system to supervisors that will eliminate mundane routine meetings and boost employee productivity. Our target customers are managers and project leaders who see value in team insights and a smooth flow of work. First, employees are asked to fill in a short questionnaire through Power Apps about their current tasks and issues. Once every employee submits the form, a summary is generated and posted to Teams so managers can check progress blockers and automatically schedule a meeting. Finally, we connect the information with Power BI where managers can see employee workload and issues. 

## Instructions

1. Run the Power App `Maverick Questionnaire` to fill out the questionnaire that collects information on your status: work completed yesterday, agenda for today, and any issues that block workflow. 
 https://apps.powerapps.com/play/e/default-1b6f644f-0f80-4d29-ad69-9d5611bb9aa5/a/bb5e27c1-5728-46bc-b3b2-6805bfe8027e?tenantId=1b6f644f-0f80-4d29-ad69-9d5611bb9aa5&source=portal

2. The data will be stored inside an MS Excel database, where you can check to see the DB being updated. 

3. Once the forms are completed among employees, we use Power Autommate to send the dashboard of user statuses and a BI of team insights to the group teams channel. 

4. Inside the Power App Dashboard `Maverick Dashboard`, a manager can schedule meetings with employees that seek help at a time where both members are available. Click the Button that says 'Schedule Meeting' to create a meeting inside the outlook calendar. 
https://apps.powerapps.com/play/e/099b9359-423f-eb0f-a550-48c33843b014/a/e775d0d5-4029-4cbc-9d35-0a983c9c5cf8?tenantId=78aac226-2f03-4b4d-9037-b46d56c55210&source=portal

5. In the BI `Maverick Insights`, you can see the trends and charts generated from the aforementioned excel database. 
