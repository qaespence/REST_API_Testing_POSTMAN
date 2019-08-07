
# REST API Testing using Postman

  * [GoREST API](#gorest-api)
    + [Resources Tested](#resources-tested-)
    + [Test cases](#test-cases-)
      - [Users](#users)
      - [Posts](#posts)
      - [Comments](#comments)
      - [Albums](#albums)
      - [Photos](#photos)
	  


> This is a project area for practicing Rest API testing using Postman.

## GoREST API
Testing various REST API methods on the GoREST API website.

### Resources tested
  * Users
  * Posts
  * Comments (TBD)
  * Albums (TBD)
  * Photos (TBD)

### Test cases

####  Users
##### HEAD/OPT
  1. Show overview info of the Users listing
  2. Show the supported verbs of Users
##### GET
  3. List all users
  4. List users by name
  5. List users by gender
  6. List users by DOB
  7. List users by email
  8. List users by phone
  9. List users by website
  10. List users by address
  11. List users by status
  12. Return the details of user by ID
##### POST (deprecated)
  13. Create a new user (deprecated)
##### PATCH/PUT
  14. Update a user using PATCH
  15. Update a user using PUT
  16. Delete the user
##### Negative Tests
  17. Negative - Return details of user by bad ID
  18. Negative - Update a user using PATCH, bad ID
  19. Negative - Update a user using PUT, bad ID
  20. Negative - Delete the user but bad ID
  
#### Posts
##### HEAD/OPT
  1. Show overview info of the Posts listing
  2. Show the supported verbs of Posts
##### GET 
  3. Return the details of post by ID
  4. List posts by user ID
  5. List posts by title
  6. List posts by body
  
#### Comments
  (TBD)
  
#### Albums
  (TBD)
  
#### Photos
  (TBD)
  