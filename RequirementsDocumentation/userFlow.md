## How user will use the app?

### SignUp
- Navigate to url **(example.com/signup)**
- Enters:
    - email
    - password
    - confirm password
    - username
    - display name
    - introduction (bio)
    - uploads profile picture (ideally sqaure ratio, if not will explicitly crop the image)

### Login
- After successful signup, user will get redirected to login page **(example.com/login)**
- User will enter valid email & password.

### Reading, Liking, unLiking other peoples tweets
- After successful login, user will be redirected to homepage **(example.com/home)**
- Homepage will contain links like:
    - Home (exmaple.com/home)
    - Profile (example.com/loggedInUsersProfile)
    - Logout (will log out the user & redirect to example.com/login page)

- Homepage will contain tweets in descending order of creation, (i.e., latest tweets will be on top)
- for homescreen design refer images on `homescreenModel.md` file
- tweets on the homepage contains following details
    - Username of user who posted that tweet
    - Profile picture of that user
    - text content of the tweet
    - timestamp of the tweet creation
    - likes count of the tweet
    - Like icon can be of different color if the user has previously like the tweet, to indicate that user can unlike if he wants to
    - in the tweet, there will be link to the user's profile who have posted that tweet, the link can be appended in the username secction of the tweet

- User will like tweets
- User will unlike the tweets only if he has previously like them.


### Posting tweets
- User will be presented with a **Textbox** & a **Post button**.
- User will type text & click on the post button.
- This tweet will be displayed on the homepage after successful post operation
- The textbox & post button will stay on top of homepage
- Images  
    ![](https://imgur.com/LMSk6rA.png)




### Visiting other user's profile
- User will click on username of other person, which will redirect user to that persons profile. (example.com/user/username, example, example.com/user/jambku)
- Other user's profile might look like this  ![](https://imgur.com/4nbDGuk.png)
- User will be able to see all the tweets posted by this user(jambku)
- User can follow this user or unfollow (later)
- User can like, unlike tweets of this user from his profile page also.


### follow/unfollow workflow (later)
