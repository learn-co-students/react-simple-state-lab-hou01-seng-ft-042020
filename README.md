# San Francisco Food Trucks CLI

## Install Dependencies

For testing and development, NodeJs is required and can be downloaded here: https://nodejs.org/en/download/

Test your installation by running the following command:

```
$ node -v 
#returns 'v10.19.0'
```

--- 

## Build (MacOS)

Unzip the file into a convenient place and make sure you're in the project directory by running:

```
$ cd SanFranciscoFoodTruckCLI
```

Or if the file has been renamed

```
$ cd YOUR_FILENAME 
```

Next while in the project folder run:

```
$ npm install
```

---

## Running the Program

While in the project directory run the following command to start the program:

```
$ npm start
```

## How I would convert to a fully featured web application!

In order to develop this CLI proof of concept into a fully featured web application that effectively enhances the user experience, I am proposing the implementation of several features. I believe that users should have the ability to filter available food trucks based on the user’s current location in relation to available food trucks in a given mile-radius. Filtering options would also include the type of food served as well as the various service hours on a given day. Additionally, I would give the users the ability to post live photos of their experiences at the food trucks and also allow other users to upvote these posts. Every week the food truck with the most aggregated weekly votes would be displayed at the top of the application. The possibility of being featured at the top of the app would create a daily incentive for food truck owners, and therefore they would encourage customers to sign up for the app and upvote their photos in the hopes of being featured.

As a means to achieve the aforementioned features, I would utilize the following technology stack. For the core frontend library, I propose ReactJs because of the speed it offers the development process and performance granted by the virtual DOM. Typescript would be used for static typing, thereby allowing for a more optimal degree of scalability. This would also be able to catch type errors before runtime. To further advance the level of scalability, I would suggest ReduxJs to maintain a central application state. NextJs would be utilized for server side rendering to maximize search engine optimization. For use in persistent data storage, I would suggest MongoDb because of its flexibility in handling scaling and adding features. Lastly, I propose Mongoose to handle object relational mapping.

---

## Thank you for your time and consideration!
