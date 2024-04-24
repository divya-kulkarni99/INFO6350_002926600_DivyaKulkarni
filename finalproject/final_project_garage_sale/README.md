# final_project_garage_sale

Step # 1 : HyperGarageSale
Start a new Flutter (Android/iOS) Application project and create you first activity with layout that allows user to enter Title, Price, Description in text format in three different text fields. Provide a button to allow user to Post a new classified.

Step # 2 : HyperGarageSale - Menus and Notifications
(1) Add a SnackBar that comes up when a new post has been added.

(2) Add an Action Bar with a menu item to Post a new item. See this article for Action Bar tutorial.

Step # 3 : BrowsePostActivity
(1) Add a new widget/screen called BrowsePostsActivity.dart with Floating Action Button

(2) Define BrowsePostsActivity as a parent activity of NewPostActivity.

(3) Implement ActionBar for BrowsePostsActivity.dart 

(4) Add navigation route to navigate from BrowsePostsActivity.dart to NewPostActivity.dart when floating action button is pressed.

(5) Update your application main entry point to use BrowsePostsActivity instead of NewPostActivity.

Step # 4 : HyperGarageSale - ListView
(1) Add a ListView to BrowsePosts screen

(2) Create a database to hold new posts data

(3) Integrate ListView and corresponding adapter with database to store new posts

Step # 5 : HyperGarageSale - Camera Interactions
With each new post, allow user to take up to 4 images and attach them

Application may display thumbnails of those images on the new post form for user to preview them

When user will click on a given post on the ListView, open the post detail view

Display post details and associated thumbnails 

When clicked on thumbnail, display full-screen image with back navigation arrow

Step # 6 : HyperGarageSale - Firebase Integration
Integrate HyperGarageSale application with Firebase Services for the following

Authentication

Real-time database (Firestore)

Storing and retrieving image files (Storage)