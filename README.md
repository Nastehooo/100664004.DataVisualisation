# Health Insights Visualisation Tool  

## Overview  
The **Health Insights Visualisation Tool** is a web-based interactive platform designed to analyze **health and wealth trends** using data from the **English Longitudinal Study of Ageing (ELSA)**. Built using **React for the frontend** and **Node.js for the backend**, this tool presents complex health data through **dynamic and engaging visualisations**, allowing users to explore longitudinal trends effectively.

## Features  
- **Interactive dropdown menus** for filtering ELSA waves, gender, and regions.  
- **Dynamic scatter plots** comparing blood pressure trends between males and females.  
- **Animated charts** illustrating the relationship between income and illness rates.  
- **Choropleth maps** visualizing regional hearing aid usage.  
- **Responsive design** ensuring smooth usability across desktop and mobile devices.  
- **Help Button** guiding users in navigating the tool effectively.  

## Technology Stack  
- **Frontend:** React.js, Chart.js, D3.js  
- **Backend:** Node.js, Express.js  
- **Data Handling:** JSON-based static files (future upgrade to MongoDB/PostgreSQL)  
- **Styling:** CSS, Comfortaa font  

## Installation & Setup  

### Prerequisites  
Ensure you have the following installed:  
- [Node.js](https://nodejs.org/) (v14 or later)  
- npm or yarn  

### Steps to Install & Run Locally  
```bash
git clone https://github.com/Nastehooo/100664004.DataVisualisation.git
cd 100664004.DataVisualisation

### Setting Up the Server
cd server
npm install
node server.js

Backend is accessible at http://localhost:8000

### Setting Up the Client
Ensure that you go to another terminal

cd client
npm install
npm start

The application will be accessible at http://localhost:3000.
