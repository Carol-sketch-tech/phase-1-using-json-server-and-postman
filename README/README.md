## what is postman 
postman is an appliction that allows us to mock up frontend request without writing any javascript.

open your postman application nad post the URL in the vscode into the GET input space and paste the URL and click send. This displays the content in the JSON.

## sending data to our JSON server from Postman 
### post request 
The post request is used when we want to send data to a server .
when we send a post request , Json SERVER recognizes teh POST request and attempt to store teh article information in the database.
To send data to out server we first have to switch our post man from GET to POST.by clicking on the Get beside the URL bar.
We now need to adjust the URL were using. In htis case we are sending data that is supposed to be a new article, because of this, we dont want to ue a specific ID vvalue in the URL. instead we'll send the request to /articles