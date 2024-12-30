# Endurance_User
@settings { 
  font-size: 50;
}
<br/>
This is a Microservice which enables and handles the User related functionality of the **Endurance** (A Platform where you can improve your coding skills).<br/>

**USERS** <br/>
&emsp;**DB Schema**:<br/>
&emsp;&emsp;**USER TABLE**:<br/>
&emsp;&emsp;&emsp;**UID  USERNAME  PASSWORD  NAME**<br/>
&emsp;&emsp;**PROBLEMS TABLE:** <br/>
&emsp;&emsp;&emsp;**UID  PID SUBMITTED_CODE  No_Of_Cases_Passed Total_No_Of_Cases  DIFFICULTY** <br/>
&emsp;&emsp;**CONTENTS TABLE:** <br/>
&emsp;&emsp;&emsp;**UID CID  No_Of_Problems_Solved  Total_Problems  Rating** <br/>
&emsp;&emsp;&emsp;(Note: Based on this rating we can calculate the Avg Rating of the User) <br/>
&emsp;**API's:** <br/>
&emsp;&emsp;getUserDetails (Might need to increase get api's based on requirement) <br/>
&emsp;&emsp;login  (Future Use: Need to include google/facebook login) <br/>
&emsp;&emsp;signup (Future Use: Need to include google/facebook signup) <br/>
&emsp;&emsp;(Need to check AuthToken generation for keeping session tracking) <br/>
    
