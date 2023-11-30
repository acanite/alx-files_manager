Files Manager
This project is a compilation of back-end concepts: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files with:

User authentication via a token
Listing of all files
Uploading a new file
Changing permissions of a file
Viewing a file
Generating thumbnails for images
Core technologies
![redis](https://github.com/acanite/alx-files_manager/assets/100510532/b8acf46d-df7e-435f-ba46-63551d5e9795)![mango](https://github.com/acanite/alx-files_manager/assets/100510532/fcd8ee94-18ac-4c86-abe1-177153ff691d)![node](https://github.com/acanite/alx-files_manager/assets/100510532/32c638b3-fa5a-4a54-8790-d35c2bf3231d)

Redis	MongoDB	NodeJS
Testing and Jobs
A queueing job mechanism for creating thumbnails of photos uploaded to the application is included in the project. When a new user is created, it also leverages this feature to generate a welcome message. Bull is used in all of this.  Bull & NodeJS
![redis](https://github.com/acanite/alx-files_manager/assets/100510532/35d1463b-1e31-44dc-a593-767e4f4f19f9)![bull](https://github.com/acanite/alx-files_manager/assets/100510532/94f43b29-064f-4b04-ae81-632a3dc3f2e7)


Mocha is used in combination with Chai for testing the app.

Mocha & Chai
![moca   chai](https://github.com/acanite/alx-files_manager/assets/100510532/b6156dce-ba39-4cde-8f4d-1d5eeb0b2b1a)
Authors

Akanni Akeem Olayinka : acanite01@gmail.com
