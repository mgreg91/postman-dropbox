# DROPBOX API

INFORMATION

- Before running the test script you have to modify the `dropbox.collection.json` at **line 96** to your own file location
- The location can be anywhere on your computer, but the file name has to be `terkep.png`
- To run the newman scripts in CLI please use the following snippet: `npm run test:dropbox`

HOME TASK

1. Familiarize with Dropbox API - https://www.dropbox.com/developers/documentation/http/documentation
2. Implement at least 3 test scenarios using one of JS libraries like Axios, Got, SuperTest (it will be a plus) or Postman :

- Upload file
- Get File Metadata
- Delete file

3. Add assertions for headers, status code and body of response
4. Add script into package.json to run API tests through the CLI (if tests done in Postman use Newman tool)
5. Push API tests to the remote repository and create a Merge Request
