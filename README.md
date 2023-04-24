Velux Project 2
This is the documentation for Velux Project 2, a Vue.js project that allows users to search for and view images of various types of buildings.

Table of Contents
Getting Started
Usage
Components
Routes
Deployment
Getting Started
To get started with Velux Project 2, first clone the repository from GitHub:

bash
Copy code
git clone https://github.com/robfeketer3/Velux_Project2.git
Then, navigate to the project directory and install the necessary dependencies:

bash
Copy code
cd Velux_Project2
npm install
You can now start the development server with the following command:

bash
Copy code
npm run serve
The app should now be running on http://localhost:8080.

Usage
Velux Project 2 is a web application that allows users to search for and view images of various types of buildings. The app consists of several components and routes, which are described in more detail below.

Search
The main feature of the app is the search bar, which allows users to search for images by keyword. To search for images, simply enter a keyword in the search bar and press enter. The app will retrieve a list of images related to the keyword and display them on the page.

Image Viewer
When a user clicks on an image in the search results, the image viewer component is displayed. This component displays the image in full size and allows users to navigate through the other images in the search results using the arrow buttons.

Components
Velux Project 2 consists of several components, which are described below:

App: The main component of the app, which renders the header and the router view.
Header: The header component, which contains the search bar.
SearchResults: The component that displays the search results.
ImageCard: The component that displays an individual image in the search results.
ImageViewer: The component that displays an image in full size and allows users to navigate through the other images in the search results.
Routes
Velux Project 2 consists of two routes, which are described below:

/: The home page of the app, which displays the search bar and the search results.
/image/:id: The image viewer page, which displays an image in full size.
Deployment
To deploy Velux Project 2, first build the app for production:

bash
Copy code
npm run build
This will create a dist directory in the project folder, containing all of the necessary files for the app.

You can then deploy the app to a web server of your choice. One option is to use Netlify, which provides a simple way to deploy static sites like Velux Project 2. Simply create a new site in Netlify, connect it to your GitHub repository, and select the dist directory as the deploy folder. Netlify will then build and deploy the app automatically whenever you push changes to the repository.

That's it! You should now have a working deployment of Velux Project 2.
