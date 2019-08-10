
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
  * Comments
  * Albums
  * Photos

### Test cases

####  Users

##### HEAD/OPT
  1. Show overview info of the Users listing
  2. Show the supported verbs of Users
##### GET
  1. List all users
  2. List users by name
  3. List users by gender
  4. List users by DOB
  5. List users by email
  6. List users by phone
  7. List users by website
  8. List users by address
  9. List users by status
  10. Return the details of user by ID
##### PATCH/PUT
  1. Backup User Entry
  2. Update a user using PATCH
  3. Restore user entry from backup
  4. Backup User Entry
  5. Update a user using PUT
  6. Restore user entry from backup
##### DELETE
  1. Delete the user
##### Negative Tests
  1. Negative - Return details of user by bad ID
  2. Negative - Update a user using PATCH, bad ID
  3. Negative - Update a user using PUT, bad ID
  4. Negative - Delete the user but bad ID
  
#### Posts

##### HEAD/OPT
  1. Show overview info of the Posts listing
  2. Show the supported verbs of Posts
##### GET 
  1. List all posts
  2. Return the details of post by ID
  3. List posts by user ID
  4. List posts by title
  5. List posts by body
##### PATCH/PUT
  1. Backup post Entry
  2. Update a post using PATCH
  3. Restore post entry from backup
  4. Backup post Entry
  5. Update a post using PUT
  6. Restore post entry from backup
##### DELETE
  1. Delete the post
##### Negative Tests
  1. Negative - Return details of post by bad ID
  2. Negative - Update a post using PATCH, bad ID
  3. Negative - Update a post using PUT, bad ID
  4. Negative - Delete the post but bad ID
  
#### Comments

##### HEAD/OPT
  1. Show overview info of the Comments listing
  2. Show the supported verbs of Comments
##### GET 
  1. List all comments
  2. Return the details of comment by ID
  3. List comments by post ID
  4. List comments by name
  5. List comments by email
  6. List comments by body
##### PATCH/PUT
  1. Backup comment Entry
  2. Update a comment using PATCH
  3. Restore comment entry from backup
  4. Backup comment Entry
  5. Update a comment using PUT
  6. Restore comment entry from backup
##### DELETE
  1. Delete the comment
##### Negative Tests
  1. Negative - Return details of comment by bad ID
  2. Negative - Update a comment using PATCH, bad ID
  3. Negative - Update a comment using PUT, bad ID
  4. Negative - Delete the comment but bad ID
  
#### Albums

##### HEAD/OPT
  1. Show overview info of the Albums listing
  2. Show the supported verbs of Albums
##### GET 
  1. List all albums
  2. Return the details of album by ID
  3. List albums by user ID
  4. List albums by title
##### PATCH/PUT
  1. Backup album Entry
  2. Update an album using PATCH
  3. Restore album entry from backup
  4. Backup album Entry
  5. Update an album using PUT
  6. Restore album entry from backup
##### DELETE
  1. Delete the album
##### Negative Tests
  1. Negative - Return details of album by bad ID
  2. Negative - Update an album using PATCH, bad ID
  3. Negative - Update an album using PUT, bad ID
  4. Negative - Delete the album but bad ID
  
#### Photos

##### HEAD/OPT
  1. Show overview info of the Photos listing
  2. Show the supported verbs of Photos
##### GET 
  1. List all photos
  2. Return the details of photo by ID
  3. List photos by album ID
  4. List photos by title
  5. List photos by url
  6. List photos by thumbnail
##### PATCH/PUT
  1. Backup photo Entry
  2. Update a photo using PATCH
  3. Restore photo entry from backup
  4. Backup photo Entry
  5. Update a photo using PUT
  6. Restore photo entry from backup
##### DELETE
  1. Delete the photo
##### Negative Tests
  1. Negative - Return details of photo by bad ID
  2. Negative - Update a photo using PATCH, bad ID
  3. Negative - Update a photo using PUT, bad ID
  4. Negative - Delete the photo but bad ID
  
  