# Update/Delete
## CRUD - UPDATE
* We use the UPDATE operation when we want to change something. It can be triggered with a PUT request. Like POST, PUT can be triggered either through JavaScript or through a <form> element.
* Let’s switch things up and use JavaScript since you already know how to use <form> elements.
* For this update operation, we will create a button that replaces the first quote by Yoda to something written by Darth Vadar.
*To do this, we need to add a button into the index.ejs .
* We will also create an external JavaScript file to execute a PUT request. According to Express conventions, this JavaScript is kept in a folder called public
* We will send a PUT request when the button gets clicked. This means we need to listen to a click event.

## CRUD - DELETE
* The DELETE operation can be triggered through a DELETE request. It’s similar to the UPDATE request so this should be simple if you understand what we’ve done above.
* For this, let’s delete the first quote by Darth Vadar.
* First, we need to add a delete button to index.ejs.
* Then, we’ll trigger a DELETE request through Fetch when a user clicks the delete button.
* Since we’re deleting a quote by Darth Vadar, we only need to send Darth Vadar’s name to the server.

![image](https://s3.eu-west-2.amazonaws.com/uploads.3alampro.com/old/monthly_2016_10/mongodb-crud-operations1.png.66739c52e595c6719d3b10f7d7ed3970.png)
