# HTML Form to Google Sheets 

#### How to store data into Google sheet from an HTML form 

## 1. Create a  Google Sheet

- Put the following headers into the first row:

<img src="">

- You can add your own custom fields (Changes should be reflected in HTML form also)



## 2. Create  Google Apps Script And Publish it (Code.gs)
<img src="">

- Gotto `Tools > Script Editor…` 
- Clear the text arae
- Paste the following script and save it

<img src="">



- Go to `Run > Run Function > initialSetup`
<img src="">
- Authorize the script by sign in to your Google account
  

- Then go to  `Edit > Current project’s triggers`. 
- Click On `Add trigger` and select `doPost`

- Change the events fields to `From spreadsheet` and `On form submit`and `Save` it


## 3. Publish the project 

- Go to o `Publish > Deploy as web app…`.

`
- For `Who has access to the app:` select `Anyone, even anonymous`.
- Click On `Deploy`.
- Copy the `Current web app URL` from the dialog.`




## 6. Input your web app URL

Open the file named `index.html`. On line 12 replace `<SCRIPT URL>` with your script url:


```




