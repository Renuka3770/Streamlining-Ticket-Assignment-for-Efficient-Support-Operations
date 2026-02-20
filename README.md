Streamlining Ticket Assignment for Efficient Support Operations 
A ServiceNow-based automation project designed to streamline support ticket routing using custom tables, 
roles, groups, ACL, and Flow Designer. 
                        Team Members 
• T. Renuka – Users & Groups Creation 
• Ch. Chandra Sekhar Reddy – Roles & Custom Table Configuration 
• D. Naveen – Role & User Assignment 
            Demo 
          Watch Demo: 
   https://drive.google.com/drive/folders/14F1aUKnQiqLSv8i018CrRGtlW6QRtP0G 
     Project Overview 
This project automates ticket assignment in ServiceNow. 
When a user creates a ticket and selects an issue type, the system automatically assigns the ticket to the 
correct support group using Flow Designer automation. 
    Key Features 
• Custom table: Operations Related 
• Automated ticket assignment 
• Role-based access control 
• ACL security implementation 
• Flow Designer automation 
• Reduced manual effort 
 
�
� Technologies Used 
Layer Technology 
Platform ServiceNow (PDI) 
Layer 
Automation 
Technology 
Flow Designer 
Database 
Custom Table 
Security 
Roles & ACL 
How to Run the Project 
Step 1 — Create ServiceNow Instance 
• Go to https://developer.servicenow.com 
• Create a Personal Developer Instance (PDI) 
Step 2 — Import Update Set 
• Navigate to System Update Sets → Retrieved Update Sets 
• Click Import Update Set from XML 
• Upload update set file 
• Click Preview Update Set 
• Click Commit Update Set 
Step 3 — Verify Components 
• Operations Related table 
• Users and Groups 
• Roles 
• ACL rules 
• Flows (Regarding Certificates & Platform) 
Step 4 — Execute Project 
• Open Operations Related → New 
• Enter ticket details 
• Select Issue type 
• Click Submit 
Step 5 — Validate Automation 
• Regarding Certificates → Assigned to Certificate Group 
• Platform/Login/404/User Expired → Assigned to Platform Group 
•  
Testing 
Functional Testing 
• Verified users, groups, and roles 
• Checked table configuration 
• Validated ACL permissions 
Flow Testing 
• Created test tickets 
• Verified automatic group assignment 
• Confirmed flow execution 
Security Testing 
• Tested role-based access 
• Verified restricted access 
Authentication 
Role-based access control implemented using ServiceNow roles and ACL. 
Future Enhancements 
• Email notifications 
• SLA tracking 
• Dashboard reporting 
• Approval workflows 
Conclusion 
This project successfully automates ticket assignment in ServiceNow using Flow Designer, improving 
operational efficiency, reducing manual work, and ensuring proper ticket routing.
