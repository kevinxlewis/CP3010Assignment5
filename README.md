# cp3010Assignment5

Mongoose

1. Install mongoose package

2. Add function to backend to connect to MongoDB through mongoose.

 3. Create a schema for info related to a customer. This schema will have 3 fields. Name which is a string, movie which is a string and email which is a string and is also required.

4. Add a new route to the backend which uses the mongoose connection named /api/addInfo. This route will accept json data and save it using a mongoose model named ‘Info’.

5. Handle an error condition if the json data does not contain the correct fields. In this case return a status code of 206. Take a screenshot of a successful response and a 206 response from Nodemon.



Mocha

Please note that we are doing this in the reverse order as Test Driven Development (TDD) would normally use.

1. Install mocha, chai and request packages as dev dependencies.

2. Create a file test/server.js

3. Create a test for the /api/movies route. The test must check that the route returns a status code of 200.

4. Run the backend server and the run the test. Take a screenshot of the successful test output
