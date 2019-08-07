
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
  21. Show overview info of the Posts listing
  22. Show the supported verbs of Posts
##### GET 
  23. List all posts
  24. Return the details of post by ID
  25. List posts by user ID
  26. List posts by title
  27. List posts by body
  
#### Comments
##### HEAD/OPT
  28. Show overview info of the Comments listing
  29. Show the supported verbs of Comments
##### GET 
  30. List all comments
  31. Return the details of comment by ID
  32. List comments by post ID
  33. List comments by name
  34. List comments by email
  35. List comments by body
  
#### Albums
##### HEAD/OPT
  36. Show overview info of the Albums listing
  37. Show the supported verbs of Albums
##### GET 
  38. List all albums
  39. Return the details of album by ID
  40. List albums by user ID
  41. List albums by title
  
#### Photos
##### HEAD/OPT
  42. Show overview info of the Photos listing
  43. Show the supported verbs of Photos
##### GET 
  44. List all photos
  45. Return the details of photo by ID
  46. List photos by album ID
  47. List photos by title
  48. List photos by url
  49. List photos by thumbnail
  