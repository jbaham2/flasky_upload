Flasky with User Profile Image Upload
======

This repository contains the source code examples for Miguel Grinberg's O'Reilly book [Flask Web Development](http://www.flaskbook.com).

This repo is a work in progress. I am (with Miguel's consent) editing the source code for the user profile image to accept a user uploaded image rather than use the gravatar service. Please follow along as I will update the README.md file as I progress. This is a learning exercise and may contain mistakes and poorly written code. 

TODO:
====
*	Allow users to upload an image from the edit profile page
*	Change User model to accept the image path as a string
*	Configure image directory
*	Change EditProfileForm class to include user_uploaded_avatar
*	Edit views.py to include the designated user image attribute when the EditProfileForm is instantiated.
*	Include the url/path for the profile image in the html files, accordingly.


This is not a complete list yet and will be updated and edited as the project moves along. I will try to make edits to the list that will preserve the progression of my work as learn what the hell I'm actually talking about. 

EXPANDED TODO:
=======
*	Implement Amazon's S3 as an image server
*	Learn to build a photo album that will display multiple images

