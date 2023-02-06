/////////////////////////
Activity
**going to**  
WF_Activity_Of_Process-> WF_Activity_Of_Process_URL

**coming from any form**  
WF_Task_List  
HistoryInstanceProcess 
3. find add Activity that related to specific process

FROM WF_Activity_Of_Process and send process id

/////////////////////////

/////////////////////////
Process
1. Process start from activity 

2. can find the configurations and options to process from "WF_Process" table

3. can find all activities from "WF_Activity_Of_Process" table with

4. can't  find all forms from Process we need to find the activities from "WF_Activity_Of_Process" first then chose "WF_Activity_Of_Process_URL" column

///////////////
 find the order of activities
 find the order of forms

/////////////////////////
Form

to find the the configurations and options to form 

to find the all the data for any form we use **the En name with replace spaces with underscores (  ) =>( )** this table have all data
/////////////////////////////
