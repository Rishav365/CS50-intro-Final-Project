# CS50 Journal

## Video Demo: https://youtu.be/quupp8gXxRs

## Description:

CS50 Journal lets you store and share your stories with other users.

There four main folders: blog, media, project and users.

1. Blog folder is where web app functionality is. Most of the classes and functions are defined in blog/views.py, in blog/templates/blog folder there is main layout.html file, then there is home.html file which is made for homepage view and then there are post related files: post_confirm_delete.html, post_detail.html, post_form.html. post_confirm_delete.html makes sure that you want to delete post, post-detail.html gets post view page and post-form.html page makes you submit your post.
Django function syntax was similar to flask syntax so it was easy to get used to it. Some classes were hard to write and stackoverflow helped me lot. While writing classes I realised that I needed to know object oriented programming so I watched CS50 web programming with python and javascript course.

2. Media folder is where profile pictures are stored.

3. Project folder is nearly unchanged after Django configuration, just added some paths in urls.py file and added some lines in settings.py

4. Users folder is where user functionality is. I made it as a separate folder so that it is easy to distinguish and also can be easily used later in other projects. It has 4 html files: login.html, logout.html, profile.html and register.html. Those html files are also extended from blog/templates/blog/layout.html
The function here will be useful in other projects too.
sqlite3 database is for storing user data and posts.
Configuring databases were easy to do because Django can to it automatically.

Additionally I used pillow as a resizing tool for profile pictures and crispy-forms as a design improvement.

The following functionalities have been added to the app:

1. Register: Any person can register to make a new account.

2. Profile: A registered user can change their profile photo and also change their username.

3. Write: Users can write anything they want to post.

4. Post: users can post their writings so that other users can read their writings.

-------------------------------------------------------------------------------------------------------------------
<img width="1230" alt="Screenshot 2022-12-31 at 7 35 07 AM" src="https://user-images.githubusercontent.com/58666496/210122041-02002501-396e-4f74-9601-17d9edb9390e.png">

<img width="1231" alt="Screenshot 2022-12-31 at 7 35 46 AM" src="https://user-images.githubusercontent.com/58666496/210122046-a4791b25-21cb-4a20-ba35-51b97b2ad35b.png">

<img width="1232" alt="Screenshot 2022-12-31 at 7 36 40 AM" src="https://user-images.githubusercontent.com/58666496/210122054-20870620-2aa0-4069-aadc-ac49f40a1d9c.png">

<img width="1232" alt="Screenshot 2022-12-31 at 7 37 06 AM" src="https://user-images.githubusercontent.com/58666496/210122064-7cae8c9a-ee86-4863-bec6-b9821832073f.png">



## Installation:

1. Clone the repository to your machine.

2. Run the command **pip install -r requirements.txt**

3. Once all the dependancies have been installed, run the command **python3 manage.py runserver**

4. This should start a local server, you should now see the link to the server in your terminal.
