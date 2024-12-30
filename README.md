# Endurance_User
@settings { 
  font-size: 50;
}

This is a Microservice which enables and handles the User related functionality of the **Endurance** (A Platform where you can improve your coding skills).

**USERS**
  **DB Schema**:
    **USER TABLE**:
      **UID  USERNAME  PASSWORD  NAME**
    **PROBLEMS TABLE:**
      **UID  PID SUBMITTED_CODE  No_Of_Cases_Passed Total_No_Of_Cases  DIFFICULTY**
    **CONTENTS TABLE:**
      **UID CID  No_Of_Problems_Solved  Total_Problems  Rating**
      (Note: Based on this rating we can calculate the Avg Rating of the User)
  **API's:**
    getUserDetails (Might need to increase get api's based on requirement)
    login  (Future Use: Need to include google/facebook login)
    signup (Future Use: Need to include google/facebook signup)
    (Need to check AuthToken generation for keeping session tracking)
    
