# Shared_Grocery_List


### Step 0:
A view-only peek at how it looks and works:<br>
https://docs.google.com/spreadsheets/d/1B9GWoD3YgRPm0CSS5acHoxx2AJ5jyvvyNZEp01GGqoI

### Step 1: 
Go to the link below to make a copy of the template.<br>
https://docs.google.com/spreadsheets/d/1B9GWoD3YgRPm0CSS5acHoxx2AJ5jyvvyNZEp01GGqoI/copy  

### Step 2:
Under `Tools` select `<> Script editor`
  
### Step 3:
Select `Run` and then once the pop up appears, click `Review permissions`; it may take a few moments for the pop up to appear. 

### Step 4:
A pop out window should appear; Select `Advanced` and then `Go to grocery printer (unsafe)`
<br>A second popup page will show up; select `Allow`

### Step 5:
Go to `Triggers` found on the menu on the left of the page. It has an alarm clock icon.
<br>Select add trigger, found on the bottom right.
<br>Under `Select event type` choose `On change` and then save.
  
### Step 6: 
All done!
<br>Go back to the Sheets browser tab. Now every time the `list` tab is changed (i.e. a check mark is toggled or a new entry is made) the code will run and update the `Print` tab.

### Important Notes:
1.	The `Print` tab should never be manually updated, as it will automatically be handled by the script.
2.	Do not change the name of either spreadsheet as that will cause the code not to run.
