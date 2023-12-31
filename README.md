# Dog Adoption Website

## Introduction

Welcome to my Dog Adoption Website, a platform where potential adopters can connect with business users who are looking to find new homes for dogs. The website not only facilitates the adoption process but also provides an extensive directory of various dog breeds, curated through an external API.

  Whether you are looking to adopt or put up a dog for adoption, This platform serves as the perfect bridge to meet your needs, featuring functionalities like real-time chat with chat history storage, breed exploration, and more. 

## Getting Started

### Installation & Setup

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the necessary packages by running the following command 
```
  npm install
```
4. To start the project in a development environment with a local MongoDB setup, use the following command
```
  npm run dev
```
 Alternatively, for a production environment setup with a MongoDB cluster, use:
```
  npm start
```
5. Next, navigate to the React application directory and start the React app using:

```
  npm start
```
Upon starting the application in the production environment, initial data consisting of three cards and three users (admin, business, and normal users) will be created automatically.

to sign in the development env on local mongoDB use one of the emails:

john@gmail.com  =  business user (the 3 initial cards owner)

david@gmail.com  =  admin user

zoro@gmail.com  =  normal user

password for all: Aa123456!

NOTE! it may be needed to delete the old token if there is a problem.

to sign in the production env on cluster mongoDB use this email:

omerbenda98@gmail.com

password: Aa123456!

## Technologies Used


### Frontend - React
- Redux: Used for authentication.
- MUI: A comprehensive React UI framework.
- React Router DOM: Used for routing and navigating between pages.
- Validation: Use joi library for validation.
- Token: using JWT library for token.


### Backend - Node.js
- Express: A minimal and flexible Node.js web application framework.
- MongoDB: Used as the database to save users,cards and chats.
- Socket.io: A JavaScript library for real-time chat in web applications.
- Multer: a user can upload a file for his profile image or his cards images using multer.

## Features
- CRM Page: An admin user can delete other users or change their business status.
- Profile Page: A registered user can access and his profile using the sidebar profile section or the navbar.
- Charities And Donation Page: Users can list an amount to donate and explore different dog charaties.
- See More Page: When clicking on a breed it will dynamicaly move to the breeds page.
- User Registration: Users can register as either adopters or business users.
- Sidebar: The sidebar contains the users name, image and a list of active chats which he can access.
- Search Bar: users can search a breed by name.
- Displays: users can pick between 3 types of displays: cards, list, slide.
- External API: Utilized to retrieve detailed information about various dog breeds.
- Dog Breed Exploration: Users can explore an extensive list of dog breeds retrieved from an external API on the home page.
- Dog Adoption Cards: Business users can create, edit, and delete dog adoption cards.
- Real-Time Chat: Enables users to communicate in real time, with chat histories saved to the database.





