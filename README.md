# Photogallery-backend
Backend repository for photogallery app created with Strapi, 11ty, Cloudinary, and Tailwind CSS.

To start up the backend server - 
1. Clone the backend repository.
```
git clone git@github.com:Quadrisheriff/Photogallery-backend.git
```
2. Navigate into the backend repository.
```
cd Photogallery-backend
```
3. Install all dependecies.
```
yarn
```
4. Create a `.env` file, and add your cloudinary secrets to the `.env` file.
```
CLOUDINARY_NAME = 
CLOUDINARY_KEY = 
CLOUDINARY_SECRET =
```
  !!! Note - CLOUDINARY_NAME is your Cloudinary cloud name, CLOUDINARY_KEY is your Cloudinary API KEY, and CLOUDINARY_SECRET is your Cloudinary API SECRET. You can  retrieve these details in the account details section of the Cloudinary dashboard.
  
5. Start the backend server.
```
yarn develop
```
