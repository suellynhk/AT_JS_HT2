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
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/20952083-b925ffaa-34e9-4f16-93ac-2eae241e58e0?action=collection%2Ffork&collection-url=entityId%3D20952083-b925ffaa-34e9-4f16-93ac-2eae241e58e0%26entityType%3Dcollection%26workspaceId%3D3ef230df-58bf-432a-8f85-f0371d526c1b#?env%5BDpbox-Environment%5D=W3sia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiIzZWkzNjk5c2dqYmY1YTAiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IjNlaTM2OTlzZ2piZjVhMCIsInNlc3Npb25JbmRleCI6MH0seyJrZXkiOiJjbGllbnRfc2VjcmV0IiwidmFsdWUiOiJ4c3d6NGYxd2oxOWR2NGMiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6Inhzd3o0ZjF3ajE5ZHY0YyIsInNlc3Npb25JbmRleCI6MX1d)

#### 2. Set the environment 'Dpbox-Environment'.

#### 3. In Authorization, scroll till the button 'Get New Access Token' and click on it.

Note: You can log in with your credentials(if you are already registered) or with your google account. Please, make sure your browser allows pop ups.

#### 4. Run the collection.


## ✨ Run the collection from CLI- Command Line Interface:
#### 1. Clone this repository:
`git clone https://github.com/suellynhk/AT_JS_HT2.git`

#### 2. Navigate to the folder:
`cd AT_JS_HT2`

#### 3. Install Newman (if you don't have it installed):
`npm install -g newman`

#### 4. Run the collection:
`newman run DropboxAPI.postman_collection.json -e DropboxEnv.postman_environment.json`

#### 5. Newman Reporter (optional):
 
##### &emsp; 1. Install Newman Reporter: 
&emsp; `npm install -g newman-reporter-html`

##### &emsp; 2. Run the collection:
&emsp; `newman run DropboxAPI.postman_collection.json -e DropboxEnv.postman_environment.json -r cli,html`

##### &emsp; Note: It will create a folder named 'newman' where the html file will be placed.

## ✨ Further improvement:
For some reason I couldn't run the collection from the CLI using Newman. 
Everything works fine on Postman, but it seems the http header 'authorization' are not beeing exported along with the collection and even adding it manually, it is still not working.
I searched about it and still haven't found a solution.