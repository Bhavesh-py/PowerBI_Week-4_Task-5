# PowerBI_Week-4_Task-5
### TASK - Do the following;
* Create a dynamic report using Parameters.
* Create a Bookmark.
* Create Row Level Security.

### Overview
* Server used for the SQL Connection is localhost:3306 and the Database used is the "Organization" created in Week 1 (SQL)
* The Bookmark is named as "dept/basic_pay" that refers to page 2.
* To perform Row Level Security, department-wise roles have been created for SDE, Tester and Analyst and the Sr. Manager role can access all the departments except Leads.

### Parameters Screenshot:
![image](https://user-images.githubusercontent.com/54022245/150679467-f743e2b8-2b58-41e4-8aa4-3defb73bc9ac.png)


### Checking Row Level Security
**Root view:**
![image](https://user-images.githubusercontent.com/54022245/150679520-9238bd06-2d2f-493a-b7e5-d40a58915b45.png)

**SDE Manager view:**
![image](https://user-images.githubusercontent.com/54022245/150679535-19055d1b-51bb-486e-b81c-4d32c5f19d72.png)


**Senior Manager view:**
![image](https://user-images.githubusercontent.com/54022245/150679560-207a3811-1a71-4e98-966a-1fa99f1b2a82.png)

NOTE: The Bookmark can be seen under the name "dept/basic_pay" in the Bookmarks pane on the right.
