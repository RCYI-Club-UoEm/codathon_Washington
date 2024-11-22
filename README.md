# Lost and Found website.
## The aim is to help people find lost items in campus.
### This is a fullstack MERN project.

If you need the repo locally, you got to have the following installed in your system.
* __Node__ - preferably a recent version and a Long Term Support(LTS) [Download Node.js](https://nodejs.org/en/download/prebuilt-installer)
* __MongoDB__ - you could install it locally [MongoDB Community](https://www.mongodb.com/try/download/community) or use their online service, the mongodb atlas. [Click Try Free](https://www.mongodb.com/products/platform/atlas-database)
* __IDE__ - this is purely dependent on what works best for you.

Now clone the repo and while in the root directory run the following command in terminal, cmd or git bash.
```
npm install
```
The command will install the dependencies for the server. After that change to the client directory.
```
cd client
```
Run the installation command to install the dependencies for the react frontend.
After that's done return to the root folder and create a .env file with the following values,
```env
MONGO_URI=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```
If you're wondering what the last three do, they help you upload images to a service called [cloudinary](https://cloudinary.com/). You get them after creatin an account.
Uploading files to a database is dicy so I used cloudinary and uploaded the link to the DB.
Then run the following command.
```
npm run dev
```
The above command runs the development servers on both the client and server. Thank to a node module called concurrently.
