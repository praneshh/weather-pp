<div align="center">

# ZeoWeather

</div>

This repository contains a full-stack project developed using the MERN stack (MongoDB, Express.js, React, and Node.js) that fetches local weather data from weather API and displays it on the dashboard. Moreover it includes following features as well :-

● Error handling for invalid rule strings or data formats (e.g., missing operators, invalid comparisons).
● Validations for attributes to be part of a catalog.


## Frontend

The frontend of this project is meticulously crafted using React, a powerful JavaScript library. It serves as the backbone of the application, handling routing and rendering of multiple sub-components, including the visually appealing dashboard page, welcoming page, and the intuitive login/register pages. These pages are thoughtfully designed utilizing a blend of HTML, CSS, and JavaScript, ensuring an engaging and seamless user experience.

To fetch data from the Weather API and interact with the MongoDB database, the project leverages the Axios library. Axios provides a convenient and efficient way to make GET/POST requests, facilitating the retrieval and manipulation of data in a secure manner. By integrating Axios, the frontend seamlessly communicates with the backend, enabling smooth data exchange between the application and external APIs.

## Backend

The backend of this project is built using Express.js and Node.js, serving as a robust bridge between the React frontend and the database. It enables seamless communication and facilitates the retrieval of weather data by leveraging Express's powerful GET/POST functionality.

For efficient data storage and management, the project utilizes a MongoDB database hosted on MongoDB Atlas. The database consists of four collections: "Active Users" for currently logged-in users and "Registered Users" for storing details of registered users like name, email, password, and city, "Daily Weather Data" to store Daily aggregates and rollups, "Hourly Weather Data" to store Hourly temperatures and others.

## Installation and Setup


# Running App

**Client-side Application**

```bash
  cd client
```

```bash
  npm install
```

```bash
  npm start
```

**Server-side Application**

```bash
  cd server
```

```bash
  npm install
```

```bash
  npm start
```




## Tech Stack

**Frontend:** React

**Backend:** Node, Express 

**Database:** MongoDB


## Feedback

If you have any feedback, please reach out to me at ahujad2808@gmail.com
