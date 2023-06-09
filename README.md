# signinsignup

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


This Application Demo
# This app starts with the animation of these two images
-![photo_2023-04-21_18-47-14](https://user-images.githubusercontent.com/87036588/233646482-e2f071f0-b993-404d-9e0c-5592a063d979.jpg)
-![photo_2023-04-21_18-47-13](https://user-images.githubusercontent.com/87036588/233646511-8a21c32d-4baf-4855-9cd3-b631d2076e3a.jpg)

# Now we are in signup screen, here we have three fields we have to put information on them after we click the button we sign up the app with the given information but we can't use app until we verify our email.
-![photo_2023-04-21_18-46-58](https://user-images.githubusercontent.com/87036588/233648471-93d8e6af-6710-4353-ae28-a64dc7e50a4f.jpg)
-![photo_2023-04-21_18-46-57](https://user-images.githubusercontent.com/87036588/233648517-818eef91-7e33-47d3-9c84-d5e98c74009e.jpg)
-![photo_2023-04-21_18-47-12](https://user-images.githubusercontent.com/87036588/233648557-3c2bc9ec-9211-4fc8-8dd3-130ab2eea73a.jpg)
-![photo_2023-04-21_18-47-10](https://user-images.githubusercontent.com/87036588/233648584-9a9f9c3c-bfed-4f24-b33a-79f498ad9c7d.jpg)
-![photo_2023-04-21_18-47-09](https://user-images.githubusercontent.com/87036588/233651987-d4a6ad7b-4b8e-442a-91cd-75a555147b11.jpg)

# After we verified our email our sign up information is saved on firebase database and we can open the app again and we automatically enter the first (Home) screen of this app.
-![photo_2023-04-21_18-46-55](https://user-images.githubusercontent.com/87036588/233658656-e94f558b-7a07-4e58-81f4-587884041403.jpg)
-![photo_2023-04-21_18-47-07](https://user-images.githubusercontent.com/87036588/233649067-9d1158e0-0f18-4b66-b31e-7b410d7f6b3a.jpg)

# In this screen,for now we have three fuctionalities that we can do currently-
1. we can sign out our current account and delete the account if we don't want to use this account further
-![photo_2023-04-21_18-47-07](https://user-images.githubusercontent.com/87036588/233650700-9dec61de-dacd-446c-acd5-50fa106bd2e8.jpg)

# If we select delete option then we move to the signup screen again to create a new account and if we select signout option then we move to the signin screen again 
But there are some signin process rules to remember-
a. fill in the correct information that you have written while signing up if not, it shows that this user email or password is wrong/incorrect/does not exist.
b. even after filling correct detail your account is sure to be verified when you signed up or else  you can not use this application
c. if you want to use options like Sign in with Google or a phone number for that you have to link your account when you signin to the app with your email and password. In this way, one authentication id can be linked with three providers & you can log in by selecting one of the options.

2. Now for linking your gmail/password authentication account with Google and Phone Number authentication, click the bottom button link an account then you can see options to select providers. 
-![photo_2023-04-21_18-47-06](https://user-images.githubusercontent.com/87036588/233650895-52f1ba3b-0c86-4259-8a69-ad266733ee9a.jpg)

3. we can move to next screen by clicking the bottomright button where we can write some text that we want to post and upload the image and write image description.
-![photo_2023-04-21_18-47-08](https://user-images.githubusercontent.com/87036588/233651625-21de03f8-75a9-4955-b164-0bd5d7ea6a3b.jpg)

# How to upload image- first click the button upload image now you were in new screen where you click the button select image and select the options from gallery or camera after selecting option it will ask your permission to access gallery or camera only for the first time, after accepting request you can select image and write the description of image in the textfield and click the done button and move the back first screen.
-![photo_2023-04-21_18-47-05](https://user-images.githubusercontent.com/87036588/233653693-918b7f59-2cef-479a-8ab8-676e6b626e5a.jpg)
-![photo_2023-04-21_18-47-04](https://user-images.githubusercontent.com/87036588/233653736-d0a3bb4f-1152-44f8-b97a-8002be24dcc1.jpg)
-![photo_2023-04-21_18-47-02](https://user-images.githubusercontent.com/87036588/233653891-1d5c22ca-3694-4209-a095-e114f7b0367f.jpg)
-![photo_2023-04-21_18-47-00](https://user-images.githubusercontent.com/87036588/233654058-2d6173c4-2be1-4243-8711-d884d85eb101.jpg)

# Now as you can see,I added two contents in the one i did not provide image and its description and in the other one did not provide text by intentionally, as you can see there are icon buttons one is on blank area in image shape after we click on this button we move to image upload screen and the other two buttons are on both of texts at the right end, after we click on them we have chance/option to update the texts by editing previous one
- ![photo_2023-04-21_18-47-01](https://user-images.githubusercontent.com/87036588/233657397-afed9023-81c4-45a3-953e-6e8418b3982a.jpg)
-![photo_2023-04-21_18-47-00](https://user-images.githubusercontent.com/87036588/233657838-ad65ed2c-0eb3-4333-b381-afa74e596393.jpg)
-![photo_2023-04-21_19-36-17](https://user-images.githubusercontent.com/87036588/233657963-2bc3c9ba-b288-4600-9fad-d69c75fe0ad6.jpg)
-![photo_2023-04-21_18-46-59](https://user-images.githubusercontent.com/87036588/233686611-0b87663a-99d1-417b-a61f-4aafe420a085.jpg)

In the last photo you had seen some kind of small circle image on the screen actually, that is a refresh indicator that we see after we refresh our screen because, after any modification in data on the database, our app UI takes some time to change the contents so you can wait or refresh the screen.

# Now at last two sign in ways-

-![photo_2023-04-21_22-06-39](https://user-images.githubusercontent.com/87036588/233689409-c381ea1d-3b7d-4959-8f6e-82c52fc2bf0c.jpg)
-![photo_2023-04-21_22-06-42](https://user-images.githubusercontent.com/87036588/233689475-acd17077-67b4-4571-af06-39ac829cef07.jpg)
-![photo_2023-04-21_22-06-38](https://user-images.githubusercontent.com/87036588/233689527-317d7c3c-8bd0-4b5b-b537-e1c60f2dea3d.jpg)

![Screenshot_2023-04-21-22-41-50-092_com miui gallery 1](https://user-images.githubusercontent.com/87036588/233696230-3dde2e1c-4934-4970-b867-90aa94446eb1.jpg)

Result from both screen-
-![photo_2023-04-21_18-46-59](https://user-images.githubusercontent.com/87036588/233689869-52f79651-893b-4121-9100-51e441917041.jpg)



