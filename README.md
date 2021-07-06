
React Photo Gallery
React and Node Photo Gallery

Cloudinary

Cloudinary is used to store the images
A cloundinary account is needed
https://cloudinary.com/users/register/free
signup for the free tier account.

----------------------

Start the server
Clone the repo

----------------------

From the Cloudinary dashboard, 
Copy the API_KEY, CLOUD_NAME, and API_SECRET

create a new file called .env
in the api directory

paste the API_KEY, CLOUD_NAME, and API_SECRET info in here:

API_KEY={YOUR_API_KEY}
CLOUD_NAME={YOUR_CLOUD_NAME}
API_SECRET={YOUR_API_SECRET}

**** PLEASE MAKE SURE TO ADD .env IN THE api/.gitignore file ****

**** API_KEY, CLOUD_NAME, and API_SECRET SHOULD NOT BE PUSHED TO GITHUB ****

----------------------

In a terminal run the following from the API folder:

npm install
npm run server

verify it's working by going to localhost:7000/photos in Postman or Chrome

----------------------

Run the Frontend
Verify that the Node server (in the API folder) running or the frontend won't work.

----------------------

Clone the repo

create a new file called .env

in the client directory

add in the following:

REACT_APP_API_URL=http://localhost:7000

If you change the port, the node server runs on for whatever reason make sure to change it here too

Open a terminal and run the following from the CLIENT folder:

npm install
npm start

The app should be running on localhost:3000