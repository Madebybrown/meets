# **Meets**
**Meet new people, make new connections with Meets!**

***Meets*** is a social media app that allows users to connect with others who share similar interests and hobbies. Whether you're looking to make new friends, find a workout buddy, or meet someone special, ***Meets*** makes it easy to connect with like-minded individuals in your area. With features such as image sharing, commenting, and personal profiles, ***Meets*** is the perfect platform for building meaningful relationships and expanding your social circle. So why wait? Visit [Meets.com](https://meets.herokuapp.com/) today and start meeting new people!

![AmIResponsive](ReadMeAssets/amiresponsive.png)

## Live Site
[www.meets.com](https://meets.herokuapp.com/)

## Live Drf Api
[drf-api99.com](https://drf-api99.herokuapp.com/)

## Repositories
[Meets Repository](https://github.com/Madebybrown/meets)

[Drf-api Repository](https://github.com/Madebybrown/drf-api)

# **Features**

- **Navigation Bar**
    - Visible on all pages to make it easy for user to navigate between pages, displays different options if your logged in or logged out.

*Logged Out*
![NavbarLoggedOut](ReadMeAssets/navbarloggedout.png)
*Logged in*
![NavbarLoggedIn](ReadMeAssets/navbarloggedin.png)

- **Sign Up Page**
    - Allows users to sign up and create an account to reap the benefits of more useful features when logged in.

![SignUp](ReadMeAssets/signup.png)

- **Sign In Page**
    - Allows users to sign in.

![SignIn](ReadMeAssets/signin.png)

- **Popular Profiles**
    - Displays the profiles with the most followers, a cool feature to allow users to easily access the most followed profiles.

![PopularProfiles](ReadMeAssets/popularprofiles.png)

- **Profile Page**
    - The users personal profile page, shows how many posts a user has created, how many followers they have and how many profiles they are following, it also displays a "bio" section and all the posts the user has posted underneath.

![ProfilePage](ReadMeAssets/profilepage.png)

- **Edit Profile**
    - The user has the option to edit their profile bio, image, username and password.

![EditProfilePage](ReadMeAssets/editprofilepage.png)

**Edit profile bio and image**
![EditProfilePageTwo](ReadMeAssets/editprofilepagetwo.png)

**Edit username**  
![EditUsername](ReadMeAssets/editusername.png)

**Edit password**  
![EditPassword](ReadMeAssets/editpassword.png)

**Add posts**
-  A feature to let the user upload images with titles and captions.
![AddPosts](ReadMeAssets/addposts.png)

**Edit posts**
-  A feature to let the user edit their uploaded posts.
![EditPosts](ReadMeAssets/editposts.png)

**Posts**
-  Let's other users see the uploaded posts so they can leave a comment and a like.
![Posts](ReadMeAssets/posts.png)

**Add Post Comment**
-  
![AddPostComment](ReadMeAssets/addpostcomment.png)

# **Features left to implement**
- Private chat
- Bookmarking images
- Delete/Pause personal account
- Security check before deleting a post Example: *"Are your sure you want to delete this post?"*

# **Testing**

## **Sign Up** | 

1 - Feature is expected to promt the user to insert a username and password when the user tries to sign up without entering a username and password.
    
- *Tested the feature by trying to sign up without entering a username and a password.*

- *The feature acted as expected and promted the user to insert a username and a password.*

2 - Feature is expected to take the user to the sign in page when clicked if the fields are filled with a valid username and password.

- *Tested the feature by trying to sign up with a authurized username and password*.

- *The feature acted as expected and took the user to the sign in page.*

## **Sign In** | 

1 - Feature is expected to promt the user to insert a valid username and password when the user tries to sign in without entering a username and password.
    
- *Tested the feature by trying to sign in without entering a username and a password.*

- *The feature acted as expected and promted the user to insert a username and a password.*

2 - Feature is expected to take the user to the home page when clicked if the fields are filled with an authorozed username and password.

- *Tested the feature by trying to sign in with an authurized username and password*.

- *The feature acted as expected and took the user to the home page.*

## **Add Post** | 

1 - Feature is expected to promt the user to insert a title and an image when the user tries to create a post without entering a title and an image.
    
- *Tested the feature by trying to create a post without entering a title and an image.*

- *The feature acted as expected and promted the user to insert a title and an image.*

2 - Feature is expected to take the user to the uploaded posts page when "create" is clicked if the fields are filled with a valid title and image.

- *Tested the feature by trying to create a post with a valid title and image*.

- *The feature acted as expected and took the user to the uploaded posts page.*

## **Delete Post** | 

1 - Feature is expected to delete a post when clicked.
    
- *Tested the feature by trying to delete a post.*

- *The feature acted as expected and deleted a post.*

## **Edit Post** | 

1 - Feature is expected to take the user to the edit post page.
    
- *Tested the feature by trying to click the edit icon.*

- *The feature acted as expected and took the user to the edit post page.*

## **Edit Post Page** | 

1 - Feature is expected to promt the user to insert a title if the user tries to edit a post by removing the title.
    
- *Tested the feature by trying to edit a post by removing the title.*

- *The feature acted as expected and promted the user to insert a title.*

2 - Feature is expected to take the user to the uploaded posts page when "save" is clicked if the fields are filled with a valid title.

- *Tested the feature by trying to create a post with a valid title*.

- *The feature acted as expected and took the user to the uploaded posts page.*

## **Post Comments** | 

1 - Feature is expected to do nothing if the user tries to post a comment without any text content.
    
- *Tested the feature by trying to create an empty comment.*

- *The feature acted as expected and did nothing.*

2 - Feature is expected to post a comment if the comment field is filled with text.

- *Tested the feature by trying to create a comment with text content*.

- *The feature acted as expected and created a comment under the picture.*

## **Follow / Unfollow** | 

1 - Feature is expected to update and *increase* the followers count of the followed user and the following count of the account owner pressing follow.
    
- *Tested the feature by trying to follow an account.*

- *The feature acted as expected updated the fields accordingly.*

2 - Feature is expected to update and *decrease* the followers count of the unfollowed user and the following count of the account owner pressing unfollow.
    
- *Tested the feature by trying to unfollow an account.*

- *The feature acted as expected updated the fields accordingly.*

## **Like / Unlike Posts** | 

1 - Feature is expected to update and *increase* the like count of the post being liked and add the post to the users liked section in the navbar.
    
- *Tested the feature by trying to like a post.*

- *The feature acted as expected updated the fields accordingly and added the post to the liked section.*

2 - Feature is expected to update and *decrease* the like count of the post and remove the post from the liked section.
    
- *Tested the feature by trying to unlike a post.*

- *The feature acted as expected, updated the fields accordingly and removed the post from the like section.*

## **Search Posts** | 

1 - Feature is expected to filter posts by usernames and titles when used.
    
- *Tested the feature by trying to filter posts.*

- *The feature acted as expected and updated the posts accordingly.*

# **Deployment**
The project was deployed using Heroku.
 - Steps for deployment:
    - First, when on the Heroku dashboard, click new up to your right-hand side, this will toggle a drop down.
    - Click on "Create new app", this will take you to a new page.
    - Here you choose your app name, and your region, and then you click "Create app" down on the left-hand side, this will take you to a new page.
    - On this page, you first click on the settings tab.
    - Here you scroll down until you see the button with "Reveal Config Vars" on it, click it!
    - Write you environment variables here and press add. 
    - Now scroll up to the top of the page and press the "Deploy" tab and then press GitHub.
    - Search for the repository you want to deploy.
    - Press connect.
    - Scroll down until you find "Enable Automatic Deploys" and "Deploy Branch", press them, and wait while your app is building.
    - Building app
    - App build is finished

# **Credits**
- 