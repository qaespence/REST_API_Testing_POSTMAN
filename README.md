
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
Site URL: https://gorest.co.in

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
##### HEAD/OPT
  1. Show overview info of the Comments listing
  2. Show the supported verbs of Comments
##### GET 
  3. Return the details of comment by ID
  4. List comments by post ID
  5. List comments by name
  6. List comments by email
  7. List comments by body
  
#### Albums
##### HEAD/OPT
  1. Show overview info of the Albums listing
  2. Show the supported verbs of Albums
##### GET 
  3. Return the details of album by ID
  4. List albums by user ID
  5. List albums by title
  
#### Photos
##### HEAD/OPT
  1. Show overview info of the Photos listing
  2. Show the supported verbs of Photos
##### GET 
  3. Return the details of photo by ID
  4. List photos by album ID
  5. List photos by title
  6. List photos by url
  7. List photos by thumbnail
  