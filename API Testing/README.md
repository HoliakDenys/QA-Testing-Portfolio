API Testing

This folder contains tests for the public API jsonplaceholder.typicode.com using Postman. The tests cover different types of HTTP requests such as GET, POST, PUT, and DELETE.

Overview
The API testing collection includes four types of requests:
1. GET: Retrieves a list of posts from the API.
2. POST: Creates a new post.
3. PUT: Updates an existing post.
4. DELETE: Deletes a post.

Each request includes tests to validate the expected responses, such as checking for correct status codes, verifying response content, and ensuring the API behaves expected.

How to use
1. Import the Collection:
   Open Postman.
   Go to the Collections tab and click Import.
   Choose the JSON file for the collection from this directory.
2. Run the requests:
   After importing the collection, you can run each request individually in Postman.
   The tests are automatically executed, and results will be shown in Postman's Test Results tab.

API Endpoints Tested
GET:    https://jsonplaceholder.typicode.com/posts
POST:   https://jsonplaceholder.typicode.com/posts
PUT:    https://jsonplaceholder.typicode.com/posts/1
DELETE: https://jsonplaceholder.typicode.com/posts/1

Test Included
GET: Verifies that the API returns a status code 200 (OK).
POST: Verifies that the response body of the POST request contains the correct data. 
PUT: Verifies that the response body of the PUT request contains the updated data for the post.
DELETE: Verifies that the post has been successfully deleted after a DELETE request.
