# AT_JS_HT2

Home Task 2 - Test automation with JS ([EPAM Training](https://training.epam.com/)).

Repository created for [Dropbox API](https://www.dropbox.com/developers/documentation/http/documentation) testing.

## ✨ Technologies used:
- [Postman](https://www.postman.com/)

- [Newman](https://www.npmjs.com/package/newman)

## ✨ Prerequisite:
- [Node.js](https://nodejs.org/)

## ✨ Run the collection in Postman:
#### 1. Fork the collection into your workspace:
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/20952083-158cef80-664d-48f0-93ad-2569bf4e3031?action=collection%2Ffork&collection-url=entityId%3D20952083-158cef80-664d-48f0-93ad-2569bf4e3031%26entityType%3Dcollection%26workspaceId%3D3ef230df-58bf-432a-8f85-f0371d526c1b#?env%5BDropbox%5D=W3sia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiIzZWkzNjk5c2dqYmY1YTAiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IjNlaTM2OTlzZ2piZjVhMCIsInNlc3Npb25JbmRleCI6MH0seyJrZXkiOiJyZWZyZXNoX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiejAzT0JfdVRMVHdBQUFBQUFBQUFBU2xyenR5UkVNSXY0UmVVY1lJQS05ay1Cbmt2MjZVa0J5ZTZnaFBKbzF6ciIsInNlc3Npb25JbmRleCI6MX0seyJrZXkiOiJhY2Nlc3NfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiJzbC5CUlJNcWxSVVZkcVA4UlRBQTg4bXRvcFhYRjBzNVBObE8xcWt1QXl0ZTJvaW5sUG1YZU9ZQ185dWVkTlFSa0UwZ29hWl96dGdBWkdrZkV1M0NJdG5CckFyX1dZb2pzYmpJamE3RWQ5U0NuM2NabWh0TDFxaVlfZUtPTG55OHBPN1hwaE9FMy4uLiIsInNlc3Npb25JbmRleCI6Mn1d)

#### 2. Set Environment as 'Dropbox'.

#### 3. Run the collection.


## ✨ Run the collection from CLI- Command Line Interface:
#### 1. Clone this repository:
`git clone https://github.com/suellynhk/AT_JS_HT2.git`

#### 2. Navigate to the folder:
`cd AT_JS_HT2`

#### 3. Install Newman (if you don't have it installed):
`npm install -g newman`

#### 4. Run the collection:
`newman run DropboxAPItesting_collection.json -e Dropbox_environment.json`

#### 5. Newman Reporter (optional):
 
##### &emsp; 1. Install Newman Reporter: 
&emsp; `npm install -g newman-reporter-html`

##### &emsp; 2. Run the collection:
&emsp; `newman run DropboxAPItesting_collection.json -e Dropbox_environment.json -r cli,html`

##### &emsp; Note: It will create a folder named 'newman' where the html file will be placed.
